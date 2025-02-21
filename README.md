# RecursionError in Python Factorial Function
This repository demonstrates a common error in recursive functions: the RecursionError.  The `factorial.py` file contains a function that calculates the factorial but doesn't handle negative input correctly, causing infinite recursion. The `factorialSolution.py` file provides a corrected version.

The RecursionError occurs because the function keeps calling itself without reaching a base case that stops the recursion. In this example, negative input will never reach the base case (`n == 0`), causing the stack to overflow.