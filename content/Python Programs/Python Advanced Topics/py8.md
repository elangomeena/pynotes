---
title: Py8
date: 2026-05-12
author: Your Name
cell_count: 4
score: 0
---

```python
items = ["A", "B", "C"]
it = iter(items)

print(next(it))
print(next(it))
print(next(it))
```

    A
    B
    C
    


```python
items = [1, 2]
it = iter(items)

print(next(it))
print(next(it))
# print(next(it))  # Raises StopIteration
```

    1
    2
    


```python
colors = ["red", "green", "blue"]

for color in colors:
    print(color)
```

    red
    green
    blue
    


```python
class CountUp:
    def __init__(self, limit):
        self.limit = limit
        self.current = 0

    def __iter__(self):
        return self

    def __next__(self):
        if self.current < self.limit:
            self.current += 1
            return self.current
        raise StopIteration

counter = CountUp(3)

for number in counter:
    print(number)
```

    1
    2
    3
    


---
**Score: 0**