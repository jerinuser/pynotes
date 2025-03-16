---
title: Def-Keyword
date: 2025-03-16
author: Your Name
cell_count: 12
score: 10
---

```python
#  created : 20250111
```


```python
#  https://www.scientecheasy.com/2022/09/reserved-keywords-in-python.html/
```


```python
#  def keyword

```


```python
def func():
    print("Inside Function")

```


```python
func()
```

    Inside Function



```python
#  return keyword
```


```python
def func_return():
    x = 20
    return x

def func_no_return():
    y = 50

    return y
```


```python
print(func_return())
```

    20



```python
print(func_no_return())
```

    50



```python
def func():
    x = 0
    for i in range(5):
        x += i
        yield x
```


```python
for i in func():
    print(i)
```

    0
    1
    3
    6
    10



```python

```


---
**Score: 10**