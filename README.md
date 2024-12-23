# PHP Loose Comparison Pitfalls

This example demonstrates a common yet subtle error in PHP related to loose comparison (==) in conditional statements.  Loose comparison can lead to unexpected behavior, particularly when dealing with values that can be evaluated as boolean false (e.g., 0, "", [], false, null).

The `bug.php` file showcases a function that uses loose comparison.  The `bugSolution.php` file provides the corrected version using strict comparison (===).  The difference in output highlights the potential for errors when using loose comparison.

**Key takeaway:**  Always prefer strict comparison (===) in PHP conditional statements unless you explicitly intend for loose comparison behavior.