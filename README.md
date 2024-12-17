# Square Root Bisection Method

This project provides a Python implementation of the square root calculation using the **bisection method**. The function approximates the square root of a given number by iteratively narrowing down the range of possible values until the result meets a specified tolerance or a maximum number of iterations is reached.

## Features
- Calculates the square root of non-negative numbers.
- Handles edge cases such as `0` and `1`.
- Adjustable tolerance for approximation precision.
- Maximum iteration limit to avoid infinite loops in cases of non-convergence.

## Usage
### Function Definition
```python
def square_root_bisection(square_target, tolerance=1e-7, max_iterations=100):
    ...
