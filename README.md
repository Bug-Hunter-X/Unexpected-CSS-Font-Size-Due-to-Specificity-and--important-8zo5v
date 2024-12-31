# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS specificity, the `!important` declaration, and the order of selectors.  The unexpected behavior arises from the combination of these elements, highlighting the importance of carefully considering CSS selector specificity.

The `bug.css` file contains the problematic CSS code. `bugSolution.css` provides a possible solution by removing unnecessary use of `!important` and carefully re-evaluating the order and specificity of selectors.