---
title: Vowels-Str
date: 2025-01-12
author: Your Name
cell_count: 3
score: 0
---

```python


```


```python
def count_vowels(s):
    vowels = "aeiouAEIOU"
    count = 0
    i = 0
    while i < len(s):
        if s[i] in vowels:
            count += 1
        i += 1
    print("Number of vowels:", count)

# Example usage
count_vowels("hello world")

```

    Number of vowels: 3



```python

```


---
**Score: 0**