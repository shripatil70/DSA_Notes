# Sliding Window

Used for subarray problems.

The sliding window technique is an optimization method used in computer science for problems involving contiguous subarrays or substrings within a linear data structure (like an array or string).

It optimizes the time complexity of solutions from potentially O(n²) or O(n³) down to O(n) by avoiding redundant calculations.

## Example:
- **Window size:** k
- Move window across array.

## Core Concept:
Instead of using nested loops to process every possible sub-segment from scratch, the sliding window maintains a dynamic range (the "window") which moves incrementally through the data. At each step, it reuses the computations from the previous window by:
- Adding the new element that enters the window from the right.
- Removing the element that leaves the window from the left.

## When to Use It:
The sliding window technique is applicable to problems that require finding an optimal value (maximum, minimum, longest, shortest) for a contiguous sequence that satisfies certain conditions. Key indicators include:
- The problem involves linear data structures like arrays or strings.
- It asks for properties of contiguous subarrays or substrings.
- A brute-force solution involves nested loops and repeated calculations.

## Types of Sliding Windows:
There are two primary types of sliding windows:
1. **Fixed-Size Window:**
the window size (k) remains constant throughout the process. The algorithm calculates the result for the initial window, then slides it one element at a time, updating the result incrementally. This is used for problems like finding the maximum sum of a subarray of a given size.
2. **Variable-Size Window:**
the window size changes dynamically based on specific conditions. The window expands from the right until a condition is met, then contracts from the left to find the optimal size (e.g., shortest or longest) that satisfies the criteria. This is useful for problems like finding the longest substring without repeating characters.

## Advantages:
- **Optimized Time Complexity:** Significantly reduces runtime, typically to linear O(n) time.
- **Efficiency:** Avoids redundant computations by leveraging results from previous windows.
- **Memory Efficient:** Often operates in-place, requiring minimal extra space (O(1) in many cases, or O(k) with auxiliary data structures like hash maps).

## Common Problems Solved:
- Finding the maximum sum of any contiguous subarray of a specific size K.
- Finding the longest substring in a string that does not contain repeating characters.
- Finding the smallest contiguous subarray whose sum is greater than or equal to a target value.
- String pattern matching.

## Problems:
1. Maximum sum subarray
2. Longest substring
