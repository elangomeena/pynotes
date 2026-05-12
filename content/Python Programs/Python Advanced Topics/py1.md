---
title: Py1
date: 2026-05-12
author: Your Name
cell_count: 3
score: 0
---

```python
squares = [x**2 for x in range(5)]
print(squares)
```

    [0, 1, 4, 9, 16]
    


```python
even_numbers = [x for x in range(10) if x % 2 == 0]
print(even_numbers)
```

    [0, 2, 4, 6, 8]
    


```python
matrix = [[i * j for j in range(3)] for i in range(3)]
print(matrix)
```

    [[0, 0, 0], [0, 1, 2], [0, 2, 4]]
    


---
**Score: 0**