---
title: Move-Zero
date: 2025-01-12
author: Your Name
cell_count: 5
score: 5
---

```python


```


```python
def move_zeroes(lst):
    non_zero = [x for x in lst if x != 0]
    zeroes = [0] * lst.count(0)
    result = non_zero + zeroes
    print("List after moving zeroes:", result)

# Example usage
move_zeroes([0, 1, 0, 3, 12])
move_zeroes([0, 0, 0])
```

    List after moving zeroes: [1, 3, 12, 0, 0]
    List after moving zeroes: [0, 0, 0]



```python
# Split a List into Two Based on a Condition
```


```python
def split_list(lst, condition):
    true_list = [x for x in lst if condition(x)]
    false_list = [x for x in lst if not condition(x)]
    print("Condition True:", true_list)
    print("Condition False:", false_list)

# Example usage
split_list([10, 20, 25, 30], lambda x: x % 2 == 0)
```

    Condition True: [10, 20, 30]
    Condition False: [25]



```python

```


---
**Score: 5**