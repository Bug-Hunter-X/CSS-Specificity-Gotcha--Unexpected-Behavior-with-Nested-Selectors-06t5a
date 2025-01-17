# CSS Specificity Gotcha: Unexpected Behavior with Nested Selectors

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected styling behavior.  The problem arises from the way CSS calculates selector specificity, which isn't always intuitive.

## The Problem

The `bug.css` file contains CSS rules that appear to be correctly ordered and should apply styles correctly. However, due to how specificity is calculated, the nested selector is not always the most specific.

## The Solution

The `bugSolution.css` file provides a solution.  This often involves adjusting the order or changing the selectors to ensure that the intended style is applied consistently and predictably.  It also demonstrates the importance of thorough testing and understanding of CSS specificity.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected styling applied to the child element.
4. Open `bugSolution.html` to see how to avoid this using different methods. 