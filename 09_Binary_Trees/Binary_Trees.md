# Binary Tree

## Definition

A tree where each node has at most two children.

![Binary Tree](https://miro.medium.com/max/1400/1*CMGFtehu01ZEBgzHG71sMg.png)

```
       10
      /  \
     5   20
```

## Traversals
- **Inorder:** Left → Root → Right
- **Preorder:** Root → Left → Right
- **Postorder:** Left → Right → Root
- **Level Order:** BFS traversal

## Problems:
- Maximum depth
- Diameter of tree

## Basic Operations on a Queue
The primary operations have a constant time complexity of O(1) in an efficient implementation (e.g., using a linked list or a circular array).

### Operations on Queue:
- **Enqueue:** Adds a new element to the rear of the queue.
- **Dequeue:** Removes and returns the element from the front of the queue.
- **Peek (or Front):** Returns the value of the element at the front without removing it.
- **isEmpty:** Checks if the queue contains any elements.
- **isFull:** Checks if the queue has reached its maximum capacity (only for fixed-size implementations like arrays).
[Wikipedia](https://en.wikipedia.org)

### Types of Queues:
1. **Simple Queue (Linear Queue):** The basic FIFO structure where insertion is at the rear and deletion is at the front.
2. **Circular Queue:** A linear queue where the last position is connected back to the first, allowing for efficient reuse of empty space and avoiding the "full" condition unless all slots are occupied.
3. **Priority Queue:** A specialized queue where each element has a priority. Elements with higher priority are dequeued before elements with lower priority, regardless of their arrival order.
4. **Double-Ended Queue (Deque):** A queue that allows insertion and deletion from both ends.
[W3Schools](https://www.w3schools.com)

## Real-World Applications of Queues:
Queues are fundamental in many computing and real-world systems:
> - Operating Systems: Managing processes waiting for CPU time (CPU scheduling) or other shared resources.
> - Printer Spooling: Print jobs are placed in a queue and processed by the printer one by one in order.
> - Network Communication: Routers and switches use queues to manage data packets waiting to be transmitted.
> - Algorithms: BFS algorithm for graph and tree traversal uses a queue to explore nodes systematically.
> - Customer Service: Call centers use queues to hold incoming calls until an agent is available, ensuring oldest call is answered first.
