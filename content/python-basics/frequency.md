---
title: Frequency
date: 2025-01-03
author: Your Name
cell_count: 2
score: 0
---

```python
def count_frequency(lst):
    frequency = {}
    for item in lst:
        if item in frequency:
            frequency[item] += 1
        else:
            frequency[item] = 1
    print("Element Frequencies:", frequency)

# Example usage
count_frequency([1, 2, 2, 3, 4, 4, 4, 5])
```

    Element Frequencies: {1: 1, 2: 2, 3: 1, 4: 3, 5: 1}





---
**Score: 0**