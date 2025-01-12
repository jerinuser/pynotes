---
title: Overlaoding
date: 2025-01-12
author: Your Name
cell_count: 2
score: 0
---

```python
class Box:
    def __init__(self, length):
        self.length = length

    def __add__(self, other):
        return self.length + other.length

box1 = Box(10)
box2 = Box(20)
print("Total Length:", box1 + box2)

```

    Total Length: 30



```python

```


---
**Score: 0**