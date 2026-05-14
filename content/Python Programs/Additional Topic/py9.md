---
title: Py9
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
import json

data = {"name": "Alice", "skills": ["Python", "AI", "ML"]}

pretty_json = json.dumps(data, indent=4)
print(pretty_json)
```

    {
        "name": "Alice",
        "skills": [
            "Python",
            "AI",
            "ML"
        ]
    }
    


```python
import json
from datetime import datetime

data = {"event": "login", "time": str(datetime.now())}

json_string = json.dumps(data)
print(json_string)
```

    {"event": "login", "time": "2026-05-14 11:11:56.844949"}
    


```python
import json

data = {"b": 2, "a": 1, "c": 3}
sorted_json = json.dumps(data, sort_keys=True)

print(sorted_json)
```

    {"a": 1, "b": 2, "c": 3}
    


```python
import json

def parse_api_response(response):
    try:
        data = json.loads(response)
        return data.get("status"), data.get("payload")
    except json.JSONDecodeError:
        return "error", None

response = '{"status": "success", "payload": {"id": 101}}'
print(parse_api_response(response))
```

    ('success', {'id': 101})
    


---
**Score: 0**