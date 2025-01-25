# CSS `calc()` Bug: Unitless Numbers

This repository demonstrates an uncommon bug related to using unitless numbers within the `calc()` function in CSS.  The problem arises from the browser's inconsistent interpretation of these unitless values, leading to layout discrepancies across different browsers. 

The `bug.css` file shows the problematic code, and `bugSolution.css` provides the corrected version.  The README provides a detailed explanation.

## How to Reproduce

1. Open `bug.html` in various browsers (Chrome, Firefox, Safari).
2. Observe the differing widths of the element.

## Solution

Always specify units (px, em, rem, etc.) for all numbers in `calc()` to ensure consistent and predictable results. See `bugSolution.css` for the corrected code.