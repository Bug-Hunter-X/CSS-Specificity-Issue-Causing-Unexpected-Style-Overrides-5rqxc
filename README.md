# CSS Specificity Bug

This repository demonstrates a common yet tricky bug in CSS: unexpected style overrides due to specificity issues.  The bug involves conflicting CSS selectors where a more specific selector unintentionally overrides the desired styling.  The solution provides a method to resolve the issue by carefully considering selector specificity and potentially using the `!important` flag (though with caution).

## Bug

The `bug.css` file contains the CSS code causing the issue.  The styles are not applied as expected due to a subtle specificity problem.

## Solution

The `solution.css` file demonstrates how to fix the specificity issue.  The solution involves carefully adjusting selector specificity, and explaining the reasoning behind each change. 

**Note:** While `!important` could technically override the problem, the use of it in the solution is avoided as it is best to solve the specificity problem instead. Using `!important` often leads to other hard-to-track down problems as it can override styles that you aren't aware of.