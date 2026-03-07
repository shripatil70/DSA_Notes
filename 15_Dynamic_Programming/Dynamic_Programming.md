# Dynamic Programming (DP)

Dynamic programming (DP) is an algorithmic technique used to solve complex problems by breaking them into smaller, overlapping subproblems and storing their solutions to avoid redundant computations. It is not a specific data structure itself, but rather a method of algorithm design that utilizes data structures (like arrays or hash tables) to store and retrieve these subproblem solutions efficiently.

**DP = Recursion + Memoization**

## Idea:
- Break problem
- Store result
- Reuse result

## Types:
- **Memoization:**
  - Top-down recursion.
- **Tabulation:**
  - Bottom-up table.

## Approaches to Dynamic Programming:
Dynamic programming problems are generally solved using one of two primary approaches:

### Top-Down (Memoization):
- Uses recursion to break the problem down into subproblems.
- A data structure (usually a dictionary or array, often called a "memoization table" or "cache") is used to store the results of solved subproblems.
- Before computing a subproblem, the program checks the table. If the result is already stored, it is retrieved directly; otherwise, it is computed, stored, and then returned. This avoids recalculating the same values repeatedly, transforming exponential time complexity into polynomial time complexity in many cases.

### Bottom-Up (Tabulation):
- This approach is iterative and avoids recursion.
- Starts by solving the most basic subproblems first and stores their solutions in a table (hence "tabulation").
- The solutions to smaller subproblems are then used to build up solutions to progressively larger subproblems until the original problem is solved. This approach typically uses less memory than memoization as it does not rely on the function call stack.

## Important Problems:
- Fibonacci
- Climbing stairs
- Longest common subsequence
- Knapsack

## Common Applications:
Dynamic programming is widely used in computer science for various optimization and counting problems. Common examples include:

| Problem | Description |
| --- | --- |
| Fibonacci Sequence | Calculation |
| Knapsack Problem | Maximizing value within a weight constraint |
| Longest Common Subsequence (LCS) | Finding the longest shared sequence between two strings |
| Edit Distance | Minimum operations to transform one string to another |
| Shortest Path Problems | In graphs (e.g., Bellman-Ford, Floyd-Warshall algorithms) |
| Matrix Chain Multiplication | Optimization of matrix multiplication order |
