---
title: Find-Reverse
date: 2025-01-12
author: Your Name
cell_count: 5
score: 5
---

```python

```


```python
def reverse_number(num):
    reverse = 0
    while num > 0:
        digit = num % 10
        reverse = reverse * 10 + digit
        num //= 10
    print("Reversed Number:", reverse)

# Example usage
reverse_number(1234)

```

    Reversed Number: 4321



```python
# Count the Digits in a Number
```


```python
def count_digits(num):
    count = 0
    while num > 0:
        num //= 10
        count += 1
    print("Number of digits:", count)

# Example usage
count_digits(12345)
```

    Number of digits: 5



```python

```


---
**Score: 5**