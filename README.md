# CSS calc() Unexpected Behavior
This repository demonstrates an uncommon issue with the CSS `calc()` function: unexpected results due to operator precedence and incorrect spacing.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides the corrected version.

## Problem:
The `calc()` function, while powerful, needs careful handling of operator precedence.  Improper spacing can also lead to errors.  The example in `bug.css` shows this.

## Solution:
The solution, demonstrated in `bugSolution.css`, emphasizes correct spacing and parenthesis usage to enforce the intended calculation order.