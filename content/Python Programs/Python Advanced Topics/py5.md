---
title: Py5
date: 2026-05-13
author: Your Name
cell_count: 4
score: 0
---

```python
square = lambda x: x ** 2
print(square(5))  # Output: 25
```

    25
    


```python
add = lambda a, b: a + b
print(add(10, 5))  # Output: 15
```

    15
    


```python
print((lambda x, y: x * y)(4, 5))  # Output: 20
```

    20
    


```python
numbers = [1, 2, 3, 4]

squares = list(map(lambda x: x ** 2, numbers))
print(squares)  # Output: [1, 4, 9, 16]
```

    [1, 4, 9, 16]
    


---
**Score: 0**