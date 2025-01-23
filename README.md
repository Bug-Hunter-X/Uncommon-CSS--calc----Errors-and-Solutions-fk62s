# Uncommon CSS `calc()` Gotchas

This repository demonstrates two uncommon errors related to the CSS `calc()` function and provides solutions.  `calc()` is powerful, but unexpected behavior can arise from improper usage of percentages or incorrect spacing.

## Bugs

1. **Percentage-based calculations:** Using percentages within `calc()` in a way that doesn't resolve to a fixed width leads to unexpected behavior.  For example, trying to calculate a percentage based on another percentage without a fixed reference will likely result in a calculation error.

2. **Whitespace errors:** Incorrect spacing around operators within the `calc()` function causes parsing issues. This is not always immediately obvious and can lead to subtle and difficult-to-debug problems.

## Solutions

The provided `bugSolution.css` file demonstrates corrected and improved versions of the buggy code.