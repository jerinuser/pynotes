---
title: Access-Element
date: 2025-01-25
author: Your Name
cell_count: 7
score: 5
---

```python


```


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



```


```python
# Example usage
access_list_element([1, 2, 3], 1)

```

    Element: 2



```python
access_list_element([1, 2, 3], 5)

```

    Error: Index out of range.



```python
access_list_element([1, 2, 3], "a")
```

    Error: Invalid index type.



```python

```


---
**Score: 5**