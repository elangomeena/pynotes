---
title: Py8
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
import json

data = {"name": "Alice", "age": 30, "city": "Toronto"}
json_string = json.dumps(data)

print(json_string)
```

    {"name": "Alice", "age": 30, "city": "Toronto"}
    


```python
import json

json_text = '{"name": "Bob", "age": 25}'
python_obj = json.loads(json_text)

print(python_obj)
print(type(python_obj))  # dict
```

    {'name': 'Bob', 'age': 25}
    <class 'dict'>
    


```python
import json

data = {
    "product": "Laptop",
    "price": 1200,
    "in_stock": True
}

with open("product.json", "w") as file:
    json.dump(data, file)
```


```python
import json

with open("product.json", "r") as file:
    data = json.load(file)

print(data)
```

    {'product': 'Laptop', 'price': 1200, 'in_stock': True}
    


---
**Score: 0**