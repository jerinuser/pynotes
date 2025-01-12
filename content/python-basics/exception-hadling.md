---
title: Exception-Hadling
date: 2025-01-12
author: Your Name
cell_count: 8
score: 5
---

```python
#  created : 20250111
```


```python
#  https://www.scientecheasy.com/2022/09/reserved-keywords-in-python.html/
```


```python
# Python Exception Handling Keywords

```


```python
x = 10
y = 0

try:
    z = x // y 
    print(z)

except ZeroDivisionError:
    print("Cannot divide by zero")

finally:
    print("finally block always gets executed")
```

    Cannot divide by zero
    finally block always gets executed



```python
#  assert Keyword

```


```python
x = 10 

assert x >= 10 
assert x < 10
```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[10], line 4
          1 x = 10 
          3 assert x >= 10 
    ----> 4 assert x < 10


    AssertionError: 



```python
x = 10
assert x < 10,"x is not less than 10"
```


    ---------------------------------------------------------------------------

    AssertionError                            Traceback (most recent call last)

    Cell In[13], line 2
          1 x = 10
    ----> 2 assert x < 10,"x is not less than 10"


    AssertionError: x is not less than 10



```python

```


---
**Score: 5**