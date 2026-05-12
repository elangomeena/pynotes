---
title: Py2
date: 2026-05-12
author: Your Name
cell_count: 3
score: 0
---

```python
def transform(x):
    return x * 10

result = [transform(x) for x in range(5)]
print(result)
```

    [0, 10, 20, 30, 40]
    


```python
result = [x for x in range(20) if x > 5 if x % 2 == 0]
print(result)
```

    [6, 8, 10, 12, 14, 16, 18]
    


```python
status = ["even" if x % 2 == 0 else "odd" for x in range(5)]
print(status)
```

    ['even', 'odd', 'even', 'odd', 'even']
    


---
**Score: 0**