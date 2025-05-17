---
title: Find-Lagrgest-Number
date: 2025-05-17
author: Your Name
cell_count: 2
score: 0
---

```python
def second_largest(lst):
    if len(lst) < 2:
        print("List must have at least two elements.")
    else:
        unique_list = list(set(lst))  # Remove duplicates
        unique_list.sort(reverse=True)  # Sort in descending order
        print("Second Largest Number:", unique_list[0])

# Example usage
second_largest([1, 2, 3, 4, 5])
second_largest([5, 5, 5])
```

    Second Largest Number: 5
    Second Largest Number: 5



```python

```


---
**Score: 0**