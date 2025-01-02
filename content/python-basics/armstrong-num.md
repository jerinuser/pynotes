---
title: Armstrong-Num
date: 2025-01-03
author: Your Name
cell_count: 3
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

# Example usage
is_armstrong(153)
is_armstrong(123)

```

    153 is an Armstrong number.
    123 is not an Armstrong number.



```python

```


---
**Score: 0**