# Graph

## Definition

Collection of vertices and edges.
a graph in data structure is a non-linear abstract data type consisting of a set of vertices (nodes) and a set of edges (links) that connect these vertices. Graphs are used to model real-world problems where objects are connected in a non-hierarchical way, such as social networks, transportation systems, and the World Wide Web.

### Example:

```
A -- B
|    |
C -- D
```

## Representation

### Adjacency Matrix
0 1 1
1 0 1
1 1 0

### Adjacency List
A -> B, C
B -> A

## Traversals
- **BFS**
  - Breadth first search
- **DFS**
  - Depth first search

## Problems:
- Detect cycle
- Shortest path

---

## core components:

- **Vertices (Nodes):** These are the individual data elements or points in the graph.
- **Edges (Links/Arcs):** These represent the connections or relationships between the vertices.

---

## Types of graphs:
- **Undirected Graph:** Edges do not have a direction, meaning the connection is bidirectional (e.g., a friendship on Facebook).
- **Directed Graph (Digraph):** Edges have a specific direction, indicating a one-way relationship (e.g., followers on social media).
- **Weighted Graph:** Each edge has a numerical value, or weight, associated with it, which can represent costs, distances, or time (e.g., distance between cities on a map).
- **Unweighted Graph:** Edges have no associated weight, and the focus is solely on connectivity.
- **Connected Graph:** A graph where a path exists between every pair of vertices.
- **Disconnected Graph:** A graph with isolated components where some vertices are unreachable from others.
- **Cyclic Graph:** A graph that contains at least one path that starts and ends at the same vertex.
- **Directed Acyclic Graph (DAG):** A directed graph that contains no cycles (used in project scheduling and compilers).

---

## Representation in memory:
- **Adjacency Matrix:** A 2D array (matrix) where the rows and columns represent vertices. A value in cell `(i, j)` indicates the presence (or weight) of an edge from vertex `i` to vertex `j`.
- **Adjacency List:** An array of linked lists where the index of the array represents a vertex, and each linked list contains the vertices that are adjacent (connected) to it.

---

# Common algorithms:
### Traversal Algorithms:
- Breadth-First Search (**BFS**): Explores the graph level by level, using a queue to keep track of the next vertices to visit.
- Depth-First Search (**DFS**): Explores as far as possible along each branch before backtracking, using a stack (or recursion) to manage visited nodes.
### Shortest Path Algorithms:
dijkstra's algorithm: Finds the shortest path between two nodes in a positively-weighted graph.
### Minimum Spanning Tree Algorithms:
pprim's Algorithm and Kruskal's Algorithm: Find a subset of edges that connects all vertices with the minimum possible total edge weight.
