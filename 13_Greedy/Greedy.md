# Greedy Algorithm

A greedy algorithm is an algorithmic paradigm in computer science that solves an optimization problem by making the locally optimal choice at each stage with the hope of finding a globally optimal solution.

## Greedy Algorithms

Greedy chooses a locally optimal solution.

### Example:
- Coin change.

### Steps:
1. Choose best option
2. Repeat

### Problems:
- Activity selection
- Fractional knapsack

It works step-by-step, always selecting the option that provides the most immediate benefit without considering future consequences or revisiting past decisions.

## Key Properties:
A problem must exhibit the following two properties for a greedy approach to guarantee an optimal solution:
- **Greedy Choice Property:** Making the locally optimal choice at each step must lead to a globally optimal solution. The decision made at one step does not depend on future results or choices.
- **Optimal Substructure:** The optimal solution to the entire problem contains within it the optimal solutions to its smaller sub-problems.

## Common Applications:
Greedy algorithms are used in various areas, especially in graph theory and optimization problems. Well-known examples include:
- Dijkstra's Algorithm for finding the shortest path from a single source in a graph with non-negative edge weights.
- Prim's and Kruskal's Algorithms for finding the Minimum Spanning Tree (MST) of a connected, undirected graph.
- Huffman Coding for lossless data compression, which builds an optimal prefix code based on character frequencies.
- Activity Selection Problem to select the maximum number of non-overlapping activities from a set of activities.
- Fractional Knapsack Problem where items can be divided into fractions to maximize total value within a limited capacity.

## Advantages and Disadvantages:
| Advantages | Disadvantages |
|--------------|----------------|
| Simple and easy to implement and understand. | Does not always guarantee the globally optimal solution for all problems (e.g., 0/1 Knapsack problem, Traveling Salesman Problem). |
| Generally efficient with good time complexity for appropriate problems. | Decisions are irrevocable (no backtracking), which can lead to suboptimal outcomes. |
| Can serve as heuristics to find close-to-optimal solutions for complex problems. | Proving the correctness and optimality of a greedy algorithm for a specific problem can be challenging. |

In summary, a greedy algorithm is a powerful and efficient heuristic when applicable, but its suitability must be carefully analyzed for each specific problem to ensure it yields the correct, optimal result.
