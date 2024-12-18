# CSS `content` Property Bug
This repository demonstrates a common issue with the CSS `content` property when used with pseudo-elements like `::before` and `::after`.  The example shows how using a URL within `content` inserts the content inline, potentially breaking layout.
The solution showcases how to achieve the desired effect, which might involve using background images instead for better control and predictable results.

## Bug
The `bug.css` file contains the problematic CSS that inlines an image, leading to layout issues.

## Solution
The `bugSolution.css` file demonstrates the correct approach, using the `background-image` property to place the image as a background.