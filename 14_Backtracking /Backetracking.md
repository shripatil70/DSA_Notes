# Backtracking

Used when exploring all possibilities.

Backtracking is an algorithmic technique (not a data structure itself) for solving problems by exploring all possible solutions step-by-step and undoing (backtracking) those choices that lead to a dead end or violate the problem's constraints. It is a refined form of the brute-force approach, commonly implemented using recursion and a depth-first search (DFS) pattern.

## Example:
- Sudoku solving.

## Algorithm:
1. Choose
2. Explore
3. Backtrack

## Problems:
- N Queens
- Permutations
- Subsets

## Key Characteristics:
- **Recursive Nature:** Backtracking heavily relies on recursion, using the call stack to manage the sequence of decisions and return to previous states when necessary.
- **Systematic Search:** It guarantees finding a solution if one exists by systematically exploring all possible paths, as opposed to a blind search.
- **Efficiency via Pruning:** Its primary advantage over pure brute-force is the ability to prune the search space early, avoiding unnecessary computations on branches that are guaranteed to fail.
- **Uses Data Structures:** While a technique, it uses common data structures like arrays, strings, and graphs to represent the problem state, and the recursion implicitly uses the system call stack.

## Common Applications:
Backtracking is particularly well-suited for constraint satisfaction and combinatorial problems where solutions are built incrementally and must satisfy specific rules.

### Puzzles:
- Sudoku solvers
- N-Queens problem
- Maze pathfinding.

### Combinatorics:
- Generating all permutations, combinations, or subsets of a given set.

### Graph Problems:
- Finding Hamiltonian cycles or performing graph coloring.

### Optimization:
- The Traveling Salesman Problem (though computationally expensive for large inputs)
- The Subset Sum problem.
