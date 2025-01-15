# CSS Transition Bug

This repository demonstrates a common issue encountered when using CSS transitions for background color changes on hover. The expected behavior is a smooth transition between the initial and hover states. However, in some browsers, the transition effect fails, resulting in an abrupt change in color. 

The `bug.css` file contains the problematic code, and `bugSolution.css` offers a solution to fix the issue.

## How to reproduce

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the abrupt change in background color when hovering over the list items.

## Solution

The solution involves ensuring that the initial state of the background color is explicitly defined in the element itself, rather than relying solely on the default style. Refer to `bugSolution.css` for the corrected code.