---
title: List-Frequence
date: 2025-01-12
author: Your Name
cell_count: 5
score: 5
---

```python
from collections import Counter
```


```python
def frequency():
    nums = list(map(int, input("Enter the numbers (separated by spaces): ").split(',')))
    frequency = Counter(nums)
    print("Element frequencies:", frequency)
    
```


```python
frequency()
```

    Enter the numbers (separated by spaces):  1,23,4,5,64,4,3,2


    Element frequencies: Counter({4: 2, 1: 1, 23: 1, 5: 1, 64: 1, 3: 1, 2: 1})



```python
def find_intersection(list1, list2):
    return list(set(list1) & set(list2))

list1 = [1, 2, 3, 4]
list2 = [3, 4, 5, 6]
intersection = find_intersection(list1, list2)
print("Intersection:", intersection)
```

    Intersection: [3, 4]



```python

```


---
**Score: 5**