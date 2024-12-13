# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow.  The `foo` function calculates the factorial using recursion.  However, for large inputs, the recursive calls consume too much stack space, leading to a stack overflow.

The `bug.hack` file contains the buggy code.  The `bugSolution.hack` file provides a solution using iteration to avoid the stack overflow.