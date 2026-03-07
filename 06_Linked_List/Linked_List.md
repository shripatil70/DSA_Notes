# Linked List

## What is a Linked List

A linked list is a linear data structure consisting of nodes, where each node contains data and a pointer (link) to the next node in the sequence. Unlike arrays, linked list nodes are not stored in contiguous memory locations, allowing for efficient insertion and deletion of elements without reorganizing the entire structure.

## Structure:

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.next = None
```

## Types
- **Singly Linked List**: `10 → 20 → 30 → NULL`
- **Doubly Linked List**: `NULL ← 10 ⇄ 20 ⇄ 30 → NULL`
- **Circular Linked List**: Last node points to first.

## Important Problems
- Reverse linked list
- Detect cycle
- Merge two sorted lists
