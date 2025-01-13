---
title: Sum-Positive
date: 2025-01-13
author: Your Name
cell_count: 3
score: 0
---

```python
def sum_positives(lst):
    positive_sum = sum(x for x in lst if x > 0)
    print("Sum of Positive Numbers:", positive_sum)

# Example usage
sum_positives([-1, 2, 3, -4, 5])
```

    Sum of Positive Numbers: 10



```python
def shift_list(lst, k):
    k = k % len(lst)  # Handle shifts larger than list length
    shifted = lst[-k:] + lst[:-k]
    print("Shifted List:", shifted)

# Example usage
shift_list([1, 2, 3, 4, 5], 2)
shift_list([1, 2, 3, 4, 5], 7)

```

    Shifted List: [4, 5, 1, 2, 3]
    Shifted List: [4, 5, 1, 2, 3]



```python

```


---
**Score: 0**