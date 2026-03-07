# Recursion

## Definition

A function calling itself.

## Example:
```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n-1)
```

## Important Concepts
- **Base Case**: Stops recursion.
- **Recursive Case**: Function calls itself.
- **Recursion Tree**: Used to visualize recursive calls.

## Problems
- Fibonacci
- Tower of Hanoi
- Generate subsets
