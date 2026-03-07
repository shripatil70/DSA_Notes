# Binary Search Tree (BST)

A Binary Search Tree (BST) is a hierarchical data structure that organizes elements in a sorted order, allowing for efficient search, insertion, and deletion operations. It is a specialized form of a binary tree, meaning each node has at most two children: a left child and a right child.

## Key Properties
The defining characteristic of a BST is its ordering property, which applies recursively to all its nodes and subtrees:
- The left subtree of a node contains only nodes with values less than the node's own value.
- The right subtree of a node contains only nodes with values greater than the node's own value.
- No duplicate values are generally allowed.

## Core Operations and Time Complexity
The sorted structure of a BST allows operations to eliminate half of the remaining elements at each step, similar to the binary search algorithm on an array.

| Operation | Average Case Time Complexity | Worst Case Time Complexity |
|---|---|---|
| Search | O(log n) | O(n) |
| Insertion | O(log n) | O(n) |
| Deletion | O(log n) | O(n) |

### Notes:
- **Average Case (Balanced Tree):** When the tree is balanced (its height is logarithmic with respect to the number of nodes), operations are very efficient, taking `O(log n)` time. Self-balancing BSTs, such as [AVL trees](https://www.geeksforgeeks.org/introduction-to-avl-tree/) and [Red-Black trees](https://www.geeksforgeeks.org/types-of-binary-tree/), automatically maintain this balance to ensure optimal performance.
- **Worst Case (Skewed Tree):** If elements are inserted in a sorted order, the BST can become a degenerate tree (like a linked list), and the time complexity degrades to `O(n)`.

## Applications
BSTs are widely used in computer science due to their efficient data management capabilities:
- **Database Indexing:** Used to speed up search queries in databases.
- **Symbol Tables:** Implemented in compilers to store and retrieve information about variables and functions efficiently.
- **Dynamic Sorting:** The in-order traversal of a BST naturally produces a sorted sequence of all elements.
- **Implementation of Abstract Data Types:** Used to implement dynamic sets, maps, and priority queues.

## Example: Binary Search Tree (BST)
A special binary tree with properties:
- Left subtree < Root < Right subtree

### Example Structure:
```
       10
      /  \
     5   15
```

### Operations:
| Operation | Complexity |
|---|---|
| Search | O(log n) |
| Insert | O(log n) |

### Common Problems:
- Validate BST
- Find Kth smallest element
