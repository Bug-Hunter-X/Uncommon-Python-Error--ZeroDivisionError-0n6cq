# Uncommon Python Error: ZeroDivisionError

This repository demonstrates a common yet easily overlooked error in Python: the ZeroDivisionError.  This error occurs when attempting to divide a number by zero.

The `bug.py` file contains the erroneous code. The `bugSolution.py` file offers a solution to prevent this type of error.

## How to reproduce the bug
1. Clone the repository.
2. Run `bug.py` with the argument `0` in place of `a`. This will immediately trigger the ZeroDivisionError exception.

## How to fix the bug
Refer to `bugSolution.py` for an improved version of the code which includes exception handling to gracefully manage cases where division by zero might occur.