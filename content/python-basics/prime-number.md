---
title: Prime-Number
date: 2025-01-12
author: Your Name
cell_count: 3
score: 0
---

```python

```


```python
def is_prime(num):
    if num <= 1:
        return False
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            return False
    return True

# Example usage
print(is_prime(7))  # True
print(is_prime(10)) # False
```

    True
    False



```python

```


---
**Score: 0**