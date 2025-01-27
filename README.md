# Unexpected Tailwind CSS Flexbox Layout

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities: unexpected layout behavior due to improper width management within flex containers.  Fractional widths (`w-1/2`, `w-1/3`, etc.) can interact strangely with flexbox unless the parent container's width is explicitly defined or the flex items' widths sum to 100%. 

The `bug.js` file contains code that reproduces the issue. The `bugSolution.js` offers a solution, demonstrating how to fix it.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` (or equivalent) in your browser.
3. Observe the unexpected layout: the blue div might not appear correctly.