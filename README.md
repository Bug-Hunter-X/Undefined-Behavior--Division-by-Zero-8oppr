# C Bug: Division by Zero

This repository demonstrates a common C programming error: division by zero. The code attempts to divide an integer by zero, resulting in undefined behavior. This can lead to crashes, unexpected results, or security vulnerabilities.

## The Bug

The `bug.c` file contains the problematic code. It declares two integers, `x` and `y`, with `y` initialized to zero. It then attempts to calculate `z = x / y`, which results in division by zero. 

## The Solution

The `bugSolution.c` file shows a corrected version that handles the potential division by zero gracefully. It includes an `if` statement to check if `y` is zero before performing the division. 

This example highlights the importance of careful input validation and error handling in C programming.