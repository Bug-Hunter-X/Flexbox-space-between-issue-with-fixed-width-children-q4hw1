# Flexbox space-between Issue

This repository demonstrates an uncommon bug related to using `justify-content: space-between` in a flex container with children that have fixed widths.  The expected behavior is for the items to be evenly spaced, but due to inconsistencies in browser implementation and rounding errors, this doesn't always happen.

The `bug.css` file contains the problematic code, while `solution.css` provides a workaround to ensure consistent spacing across different browsers.