# Heap

## Definition

Complete binary tree used for priority operations.
A heap is a complete, tree-based data structure satisfying the heap property: parents are always greater (max-heap) or smaller (min-heap) than their children.

## Types:

- **Min Heap**
  - Smallest element at root.
- **Max Heap**
  - Largest element at root.

## Operations:

| Operation | Complexity |
| --- | --- |
| Insert | O(log n)  -  time complexity to maintain the heap structure|
| Delete | O(log n) -  time complexity to maintain the heap structure |
| Peek | O(1) -  time to access the root element |
| Delete | O(N) -  to rearrange elements to satisfy the heap property |

## Applications:

- Priority queues
- Dijkstra algorithm
