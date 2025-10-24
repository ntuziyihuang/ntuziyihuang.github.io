+++
title = "Introduction to Python"
date = 2025-10-24
tags = ["python", "programming", "basics"]
categories = ["Programming"]
summary = "A gentle introduction to Python programming language covering syntax, variables, data types and basic control structures."
+++

Python is a versatile, high‑level programming language that prioritizes readability and ease of use.
It supports multiple programming paradigms and has a large standard library, making it suitable for everything from scripting and automation to web development and data science.

### Variables and Data Types

Variables store values that your program can manipulate.
Python is dynamically typed, so you don't need to explicitly declare a variable's type.
Common data types include `int`, `float`, `str`, `bool`, `list` and `dict`.

```python
a = 42            # integer
b = 3.14         # floating point
c = "Hello"     # string
d = True         # boolean
e = [1, 2, 3]    # list
f = {"x": 10, "y": 20}  # dictionary

print(a, b, c, d, e, f)
```

### Control Structures

Python uses indentation to denote code blocks.
Conditional statements and loops control the flow of your program.

```python
for i in range(5):
    if i % 2 == 0:
        print(f"{i} is even")
    else:
        print(f"{i} is odd")
```

### Conclusion

This note introduces Python's core syntax and features.
Subsequent articles will explore functions, modules, object‑oriented programming and practical projects.
