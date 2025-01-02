---
title: Access-Element
date: 2025-01-03
author: Your Name
cell_count: 3
score: 0
---

```python


```


```python
def access_list_element(lst, index):
    try:
        print("Element:", lst[index])
    except IndexError:
        print("Error: Index out of range.")
    except TypeError:
        print("Error: Invalid index type.")

# Example usage
access_list_element([1, 2, 3], 1)
access_list_element([1, 2, 3], 5)
access_list_element([1, 2, 3], "a")

```

    Element: 2
    Error: Index out of range.
    Error: Invalid index type.



```python

```


---
**Score: 0**