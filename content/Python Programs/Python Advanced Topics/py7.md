---
title: Py7
date: 2026-05-12
author: Your Name
cell_count: 4
score: 0
---

```python
def square_func(x):
    return x ** 2

square_lambda = lambda x: x ** 2

print(square_func(4))     # 16
print(square_lambda(4))   # 16
```

    16
    16
    


```python
employees = [
    {"name": "Alice", "salary": 5000},
    {"name": "Bob", "salary": 3000},
    {"name": "Charlie", "salary": 7000}
]

highest_paid = max(employees, key=lambda emp: emp["salary"])
print(highest_paid)
```

    {'name': 'Charlie', 'salary': 7000}
    


```python
numbers = [1, 2, 3, 4]
iterator = iter(numbers)

print(next(iterator))  # 1
print(next(iterator))  # 2
```

    1
    2
    


```python
data = [10, 20, 30]

print(iter(data))     # Iterable converted to iterator
print(isinstance(data, list))  # Iterable
```

    <list_iterator object at 0x00000192EA129240>
    True
    


---
**Score: 0**