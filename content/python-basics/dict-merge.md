---
title: Dict-Merge
date: 2025-01-03
author: Your Name
cell_count: 3
score: 0
---

```python
def merge_dicts():
    # Define the two dictionaries inside the function
    my_dict1 = {'a': 1, 'b': 2, 'c': 3}
    my_dict2 = {'d': 4, 'e': 5, 'f': 6}
    
    # Method 1: Using dictionary unpacking
    result1 = {**my_dict1, **my_dict2}
    print("Method 1:", result1)
    
    # Method 2: Using copy and update
    result2 = my_dict1.copy()
    result2.update(my_dict2)
    print("Method 2:", result2)

```


```python
# Call the function
merge_dicts()
```

    Method 1: {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5, 'f': 6}
    Method 2: {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5, 'f': 6}



```python

```


---
**Score: 0**