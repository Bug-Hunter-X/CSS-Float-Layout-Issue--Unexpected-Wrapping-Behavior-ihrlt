# CSS Float Layout Bug

This repository demonstrates a common CSS layout bug related to floating elements exceeding the width of their container.  The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers a solution using flexbox.

## Problem

When using `float: left;` and the total width of floated elements exceeds the container width, some browsers may not handle the wrapping correctly, leading to unexpected layout behavior. 

## Solution

Instead of using floats, consider using flexbox for more predictable and robust layout management. Flexbox offers superior control over alignment and distribution, avoiding common pitfalls associated with floats.

## How to Reproduce

1. Open `bug.html` in your browser.
2. Observe the layout of the divs.
3. Compare the layout to the expected layout as seen in `bugSolution.html`.