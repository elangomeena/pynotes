---
title: Py7
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
def withdraw(balance, amount):
    assert amount <= balance, "Insufficient balance"
    return balance - amount

print(withdraw(500, 600))
```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[3], line 5
          2     assert amount <= balance, "Insufficient balance"
          3     return balance - amount
    ----> 5 print(withdraw(500, 600))
    

    Cell In[3], line 2, in withdraw(balance, amount)
          1 def withdraw(balance, amount):
    ----> 2     assert amount <= balance, "Insufficient balance"
          3     return balance - amount
    

    AssertionError: Insufficient balance



```python
# Assertion
assert x != 0, "x must not be zero"

# Exception
if x == 0:
    raise ValueError("x must not be zero")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[4], line 2
          1 # Assertion
    ----> 2 assert x != 0, "x must not be zero"
          4 # Exception
          5 if x == 0:
    

    NameError: name 'x' is not defined



```python
def process_data(data):
    assert data is not None and len(data) > 0, "Data cannot be empty"
    return sum(data)

print(process_data([10, 20, 30]))
```

    60
    


```python
def process_order(order):
    assert "id" in order, "Order must contain ID"
    assert order["amount"] > 0, "Order amount must be positive"
    return "Order Processed"

order = {"id": 101, "amount": 250}
print(process_order(order))
```

    Order Processed
    


---
**Score: 0**