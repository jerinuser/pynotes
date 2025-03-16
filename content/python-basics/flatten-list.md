---
title: Flatten-List
date: 2025-03-16
author: Your Name
cell_count: 5
score: 5
---

```python

```


```python
def flatten(nested_list):
    flat_list = []
    for item in nested_list:
        if isinstance(item, list):
            flat_list.extend(flatten(item))
        else:
            flat_list.append(item)
    return flat_list

# Example usage
print(flatten([1, [2, 3], [4, [5, 6]]]))  # [1, 2, 3, 4, 5, 6]

```

    [1, 2, 3, 4, 5, 6]



```python
# Check if a List is Sorted
```


```python
def is_sorted(lst):
    return lst == sorted(lst)

# Example usage
print(is_sorted([1, 2, 3, 4]))  # True
print(is_sorted([4, 3, 2, 1]))  # False

```

    True
    False



```python

```


---
**Score: 5**