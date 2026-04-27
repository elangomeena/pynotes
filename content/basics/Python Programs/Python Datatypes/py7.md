---
title: Py7
date: 2026-04-27
author: Your Name
cell_count: 3
score: 0
---

```python
squares = [x**2 for x in range(5)]
print(squares)  # Output: [0, 1, 4, 9, 16]
```

    [0, 1, 4, 9, 16]
    


```python
numbers = [4, 1, 3, 2]

numbers.sort()
print(numbers)  # Output: [1, 2, 3, 4]

numbers.reverse()
print(numbers)  # Output: [4, 3, 2, 1]
```

    [1, 2, 3, 4]
    [4, 3, 2, 1]
    


```python
empty_tuple = ()
single_element = (10,)   # Comma required for single-element tuple
numbers = (1, 2, 3, 4)
mixed = (10, "Python", True)

print(empty_tuple)
print(single_element)
print(numbers)
print(mixed)
```

    ()
    (10,)
    (1, 2, 3, 4)
    (10, 'Python', True)
    


---
**Score: 0**