# Unexpected behavior of calc() with percentages and other units
This repository demonstrates an uncommon bug related to the CSS `calc()` function when used with a mix of percentages and other units. The expected calculation does not occur, resulting in unexpected layout or styling.

## Bug Description
The `calc()` function is not producing the expected result when combining percentages and other units (e.g., pixels). This leads to incorrect spacing, dimensions, or other visual issues.

## How to reproduce
1. Clone this repository.
2. Open `bug.css` to see the problematic code.
3. Open `bug.html` in a browser to view the unexpected result. 
4. Open `bugSolution.css` to see a possible solution.

## Solution
The solution involves understanding the context in which `calc()` is used and potential limitations when combining different units.  Sometimes, it's necessary to refactor the CSS to avoid using percentages in conjunction with other units within `calc()`, or to restructure your layout entirely.
