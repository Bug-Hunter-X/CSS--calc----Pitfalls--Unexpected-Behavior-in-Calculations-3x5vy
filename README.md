# CSS `calc()` Gotchas: Unexpected Calculation Results

This repository demonstrates some less common issues that can arise when using the CSS `calc()` function.  The `bug.css` file shows examples of these problems, while `bugSolution.css` provides corrected versions.

**Common Problems:**

* **Inconsistent Units:**  Mixing units without proper consideration (e.g., `calc(100% - 20)` instead of `calc(100% - 20px)`).
* **Operator Precedence:** Misunderstanding of how `calc()` handles different operators can lead to incorrect results.
* **Nested Calculations:**  Complex nested `calc()` expressions can become difficult to manage and debug.

This example highlights the importance of carefully writing `calc()` expressions to avoid unexpected layout behaviors.