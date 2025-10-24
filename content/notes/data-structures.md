+++
title = "Understanding Data Structures"
date = 2025-10-24
tags = ["data structures", "algorithms", "programming"]
categories = ["Computer Science"]
summary = "Overview of fundamental data structures like arrays, linked lists, stacks, queues and how to choose the right one."
+++

Data structures are ways to organize and store data efficiently to enable easy access and modification.  
Choosing the right data structure can greatly improve the performance and readability of your code.

### Arrays and Lists

Arrays (or lists in Python) are ordered collections that allow random access by index.  
They are ideal when you need fast access and iteration.

```python
items = ["apple", "banana", "cherry"]
print(items[1])  # banana
```

### Linked Lists

A linked list consists of nodes where each node contains a value and a pointer to the next node.  
They provide efficient insertions and deletions at the cost of slower random access.

### Stacks and Queues

Stacks follow a last‑in first‑out (LIFO) order and queues follow a first‑in first‑out (FIFO) order.  
They are built on top of lists or linked lists.

```python
# stack example using a list
stack = []
stack.append(1)
stack.append(2)
print(stack.pop())  # 2

# queue example using collections.deque
from collections import deque
queue = deque([1, 2, 3])
queue.append(4)
print(queue.popleft())  # 1
```

### Conclusion

Understanding how common data structures work helps you decide which one to use in different situations.  
We'll explore trees, graphs and hash tables in future posts.
