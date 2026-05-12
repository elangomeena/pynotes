---
title: Py6
date: 2026-05-12
author: Your Name
cell_count: 5
score: 5
---

```python
numbers = [1, 2, 3, 4, 5, 6]

even_numbers = list(filter(lambda x: x % 2 == 0, numbers))
print(even_numbers)  # Output: [2, 4, 6]
```

    [2, 4, 6]
    


```python
from functools import reduce

numbers = [1, 2, 3, 4]

total = reduce(lambda x, y: x + y, numbers)
print(total)  # Output: 10
```

    10
    


```python
students = [("Alice", 85), ("Bob", 72), ("Charlie", 90)]

students.sort(key=lambda x: x[1])
print(students)
```

    [('Bob', 72), ('Alice', 85), ('Charlie', 90)]
    


```python
multipliers = [(lambda x: x * n) for n in range(1, 4)]

print(multipliers)  # Output: 5
#print(multipliers)  # Output: 10
```

    [<function <listcomp>.<lambda> at 0x00000266BD9C8220>, <function <listcomp>.<lambda> at 0x00000266BD9C8360>, <function <listcomp>.<lambda> at 0x00000266BD9C8400>]
    


```python

```


---
**Score: 5**