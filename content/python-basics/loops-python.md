---
title: Loops-Python
date: 2025-05-17
author: Your Name
cell_count: 7
score: 5
---

```python
#  created : 20250111
```


```python
#  https://www.scientecheasy.com/2022/10/loops-in-python.html/
```


```python
count = 0
while count < 10:
    print('Hello world')
    count += 1
print('Loop finished')
```

    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Hello world
    Loop finished



```python
start, end = 10, 50
for num in range(start, end + 1):
    if num > 1:  # Prime numbers are greater than 1
        for i in range(2, int(num**0.5) + 1):
            if num % i == 0:
                break
        else:
            print(f"{num} is a prime number")
```

    11 is a prime number
    13 is a prime number
    17 is a prime number
    19 is a prime number
    23 is a prime number
    29 is a prime number
    31 is a prime number
    37 is a prime number
    41 is a prime number
    43 is a prime number
    47 is a prime number



```python
text = "Python is fun"
reversed_text = ""
for char in text:
    reversed_text = char + reversed_text
print(f"Original: {text}")
print(f"Reversed: {reversed_text}")
```

    Original: Python is fun
    Reversed: nuf si nohtyP



```python
text = "Loops and Logic in Python"
vowels = "aeiouAEIOU"
count = sum(1 for char in text if char in vowels)
print(f"String: {text}")
print(f"Number of vowels: {count}")
```

    String: Loops and Logic in Python
    Number of vowels: 7



```python

```


---
**Score: 5**