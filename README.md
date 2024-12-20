# Hidden CSS `calc()` Gotchas

This repository demonstrates some subtle but common errors when using the CSS `calc()` function.  These errors can be difficult to debug because they often manifest as unexpected layout issues without clear error messages in the browser's developer console.

The `bug.css` file contains examples of incorrect `calc()` usage. The `bugSolution.css` file provides the corrected versions.  The issues highlighted include:

* **Missing spaces:**  Spaces around operators in `calc()` are required.  Missing spaces will lead to calculation errors.
* **Parentheses mismatches:** Incorrect use of parentheses in nested calculations can alter the order of operations, leading to wrong results.
* **Unit mismatches:** Combining different units (e.g., `px` and `%`) without proper conversion will result in unexpected behavior.

Review the code in each file to understand how these subtle mistakes can impact layout and how they should be corrected. 