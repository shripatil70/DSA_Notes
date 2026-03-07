# 1. What is an Array

An array is a fundamental linear data structure that stores a collection of elements of the same data type in contiguous memory locations. It allows for fast, random access using numerical indices (starting at 0). Arrays have a fixed size, making them efficient for storing ordered data but less efficient for insertions/deletions.

## Examples:

```python
arr = [1, 2, 3, 4]
```

## Properties:
- Fixed size
- Fast random access
- Same data type

## Basic Operations:
| Operation | Complexity |
|---|---|
| Access | O(1) |
| Search | O(n) |
| Insertion | O(n) |
| Deletion | O(n) |

## Important Patterns:
- **Prefix Sum**
  - Used for range sum queries.
- **Sliding Window**
  - Used for subarray problems.
- **Two Pointer**
  - Used for sorted arrays.

## Common Interview Problems:
- Two Sum
- Maximum Subarray
- Rotate Array
- Product of Array Except Self
- Merge Intervals
