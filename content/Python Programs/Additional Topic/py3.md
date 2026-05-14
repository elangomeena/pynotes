---
title: Py3
date: 2026-05-14
author: Your Name
cell_count: 4
score: 0
---

```python
result = 5 & 3 | 2
print(result)
```

    3
    


```python
result = 5 + 2 ** 3 * 4 > 20 and not False
print(result)  # True
```

    True
    


```python
import keyword

print(keyword.kwlist)
```

    ['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
    


```python
import keyword

for word in keyword.kwlist:
    print(word)
```

    False
    None
    True
    and
    as
    assert
    async
    await
    break
    class
    continue
    def
    del
    elif
    else
    except
    finally
    for
    from
    global
    if
    import
    in
    is
    lambda
    nonlocal
    not
    or
    pass
    raise
    return
    try
    while
    with
    yield
    


---
**Score: 0**