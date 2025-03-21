---
title: List-Palindromnic
date: 2025-03-21
author: Your Name
cell_count: 3
score: 0
---

```python

```


```python
def is_list_palindrome(lst):
    start = 0
    end = len(lst) - 1
    while start < end:
        if lst[start] != lst[end]:
            print("The list is not a palindrome.")
            return
        start += 1
        end -= 1
    print("The list is a palindrome.")

# Example usage
is_list_palindrome([1, 2, 3, 2, 1])
is_list_palindrome([1, 2, 3])

```

    The list is a palindrome.
    The list is not a palindrome.



```python

```


---
**Score: 0**