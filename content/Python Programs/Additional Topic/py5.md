---
title: Py5
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
# Variable
total_price = 500

# Function
def calculate_total():
    pass

# Class
class UserAccount:
    pass
```


```python
import keyword

print(keyword.iskeyword("if"))      # True
print(keyword.iskeyword("value"))   # False
```

    True
    False
    


```python
class OrderProcessor:
    def calculate_tax(self, amount):
        tax_rate = 0.18
        return amount * tax_rate

processor = OrderProcessor()
print(processor.calculate_tax(1000))
```

    180.0
    


```python
x = 10
assert x > 0
```


---
**Score: 0**