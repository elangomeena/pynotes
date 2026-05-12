---
title: Py3
date: 2026-05-12
author: Your Name
cell_count: 3
score: 0
---

```python
raw = ["  apple ", " Banana", "cherry "]
cleaned = [item.strip().lower() for item in raw]
print(cleaned)
```

    ['apple', 'banana', 'cherry']
    


```python
pairs = [(x, y) for x, y in zip([1,2], [3,4])]
print(pairs)
```

    [(1, 3), (2, 4)]
    


```python
keys = ["a", "b"]
values = [1, 2]
data = {k: v for k, v in zip(keys, values)}
print(data)
```

    {'a': 1, 'b': 2}
    


---
**Score: 0**