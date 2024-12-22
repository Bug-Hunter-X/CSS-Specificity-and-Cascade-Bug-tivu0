# CSS Specificity and Cascade Bug

This repository demonstrates an uncommon bug related to CSS selector specificity and the cascade.  The issue highlights how specificity can override seemingly straightforward style declarations, potentially leading to unexpected visual results.

## Bug Description

The `bug.css` file contains CSS rules that appear simple, but produce unexpected results based on the nesting of elements. The challenge is to understand why paragraphs nested within a `div` have different colors than those that aren't.