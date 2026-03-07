# Stack

## Definition

A stack is a linear data structure that follows the Last-In, First-Out (LIFO) principle. This means the last element added to the stack is the first one to be removed, similar to a physical stack of plates where you can only add or remove the top plate.

**Key Concepts:**
- **LIFO (Last-In, First-Out):** The defining principle of a stack. The most recent item is always the first one accessible.
- **Top:** The single end of the stack where all operations (insertion and deletion) occur.
- **Stack Overflow:** A condition that occurs if you try to add an element to a stack that is already full.
- **Stack Underflow:** A condition that occurs if you try to remove an element from an empty stack.

**Last In First Out**

## Operations:

| Operation | Description |
| --- | --- |
| Push | Add element |
| Pop | Remove element |
| Peek | Top element |

## Example:
```python
stack = []
stack.append(10)
stack.pop()
```

## Applications:
- Expression evaluation
- Parenthesis checking
