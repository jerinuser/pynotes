---
title: Positive-Negative
date: 2025-03-16
author: Your Name
cell_count: 2
score: 0
---

```python
def count_numbers(lst):
    positives = 0
    negatives = 0
    zeros = 0
    for num in lst:
        if num > 0:
            positives += 1
        elif num < 0:
            negatives += 1
        else:
            zeros += 1
    print(f"Positive: {positives}, Negative: {negatives}, Zero: {zeros}")

# Example usage
count_numbers([1, -2, 0, 4, -5, 0])
```

    Positive: 2, Negative: 2, Zero: 2



```python

```


---
**Score: 0**