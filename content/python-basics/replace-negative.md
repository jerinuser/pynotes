---
title: Replace-Negative
date: 2025-01-13
author: Your Name
cell_count: 5
score: 5
---

```python


```


```python
def replace_negatives(lst):
    replaced = [x if x >= 0 else 0 for x in lst]
    print("List after Replacing Negatives:", replaced)

# Example usage
replace_negatives([-1, 2, -3, 4, -5])
```

    List after Replacing Negatives: [0, 2, 0, 4, 0]



```python
# intersection of a list 
```


```python
def list_intersection(lst1, lst2):
    intersection = [x for x in lst1 if x in lst2]
    print("Intersection:", intersection)

# Example usage
list_intersection([1, 2, 3, 4], [3, 4, 5, 6])
```

    Intersection: [3, 4]



```python

```


---
**Score: 5**