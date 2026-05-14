---
title: Py6
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
age = 18
assert age >= 18
```


```python
score = 40
assert score >= 50, "Score must be at least 50 to pass"
```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[2], line 2
          1 score = 40
    ----> 2 assert score >= 50, "Score must be at least 50 to pass"
    

    AssertionError: Score must be at least 50 to pass



```python
value = -5
assert value > 0, "Value must be positive"
```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[3], line 2
          1 value = -5
    ----> 2 assert value > 0, "Value must be positive"
    

    AssertionError: Value must be positive



```python
def calculate_square(num):
    assert isinstance(num, int), "Input must be an integer"
    return num * num

print(calculate_square(5))
```

    25
    


---
**Score: 0**