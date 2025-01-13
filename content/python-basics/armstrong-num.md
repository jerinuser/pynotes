---
title: Armstrong-Num
date: 2025-01-13
author: Your Name
cell_count: 4
score: 0
---

```python

```


```python
def is_armstrong(num):
    temp = num
    sum_of_cubes = 0
    while temp > 0:
        digit = temp % 10
        sum_of_cubes += digit ** 3
        temp //= 10
    if sum_of_cubes == num:
        print(num, "is an Armstrong number.")
    else:
        print(num, "is not an Armstrong number.")

```


```python
is_armstrong(153)
```

    153 is an Armstrong number.



```python
is_armstrong(123)
```

    123 is not an Armstrong number.



---
**Score: 0**