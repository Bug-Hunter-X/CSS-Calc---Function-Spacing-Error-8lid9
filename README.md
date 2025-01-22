# CSS Calc() Function Spacing Error

This repository demonstrates a common error encountered when using the `calc()` function in CSS.  The issue arises from incorrect spacing around the mathematical operators within the `calc()` expression.

## The Problem

The `calc()` function requires spaces around the operators (+, -, *, /) to function correctly.  Omitting these spaces will result in unexpected behavior or parsing errors.

## Example

**Incorrect:**
```css
width:calc(100%-10px);
```

**Correct:**
```css
width:calc(100% - 10px);
```

## Solution

Always ensure that there are spaces around the operators within the `calc()` function.  This simple fix will prevent errors and ensure your CSS calculations work as expected.