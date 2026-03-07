# Queue

## Definition

A queue is a **FIFO (First-In, First-Out)** structure.

It is a linear data structure where the first element added is the first one removed, similar to a line of people.

---

## Key Concepts & Operations
- **Front/Rear:** Elements are added at the rear and removed from the front.
- **Operations (O(1) complexity):**
  - `Enqueue` (add)
  - `Dequeue` (remove)
  - `Peek` (view front)
  - Checks for empty or full states.

---

## Types of Queues
- **Simple:** Strict FIFO order.
- **Circular:** Rear connects back to front for efficient space utilization.
- **Priority:** Elements are served based on priority rather than arrival order.
- **Deque (Double-Ended):** Allows insertion/deletion at both ends.

---

## Applications
Queues are essential in computing for:
- **Scheduling:** CPU task management and printer spooling.
- **Networking:** Packet buffering in routers.
- **Algorithms:** Breadth-First Search (BFS).
- **Buffering:** Handling data flow between components with different speeds.

---

## Operations:
| Operation | Description |
| --- | --- |
| Enqueue | Insert |
| Dequeue | Remove |

---

## Example:
```python
from collections import deque
default_queue = deque()
default_queue.append(10)
default_queue.popleft()
default_queue # deque([10]) after append, then deque([]) after popleft()
default_queue # empty after removal if no elements remain 
```

---

## Types:
- Circular queue
- Deque
- Priority queue
