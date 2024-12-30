# CSS Specificity Bug: Unexpected Styling

This repository demonstrates a common CSS bug related to specificity conflicts.  The bug arises from unexpected styling due to conflicting selectors with differing levels of specificity. The solution provides a clear approach to resolving this issue through careful selector ordering and understanding specificity rules in CSS.

## Bug Description

The `bug.css` file contains CSS rules that conflict due to specificity.  An element with both a class and ID selector receives an unexpected style.

## Solution

The `bugSolution.css` file demonstrates how to resolve this issue using careful selector ordering or more specific selectors. The goal is to make the style predictable and consistent.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (or create a simple HTML file using the selector classes and ID in `bug.css`).
3. Observe that the styling differs from your expectation.
4. Compare with the `bugSolution.css` file for a better approach.