---
title: Operator-Precedence
date: 2025-03-16
author: Your Name
cell_count: 27
score: 25
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/operator-precedence-in-python.html/
```


```python
# Python Precedence Operator

```


```python
# #  meaning of precedence operator:
# ------------------------------------
# Operator precedence in Python means the order in which the Python interpreter executes operators. 
# It tells the Python interpreter which operator should be evaluated first if a single statement contains more than one operator.
```


```python
def exp():
    result = exp = 3 + 5 * 4 # --> 5*4 will work first anad then will add 3
    return result
```


```python
exp()
```




    23




```python
# incorrect format of precedence 
```


```python
Avg = 5 + 10 + 20 / 3

```


```python
Avg
```




    21.666666666666668




```python
# difference 
```


```python
Avg = (5 + 10 + 20) / 3

```


```python
Avg
```




    11.666666666666666




```python
def division():
    result=(10 / 5 * 5)
    return result
```


```python
division()
```




    10.0




```python
def division2():
    result = (10 - 10 + 10 / 10 * 10)
    return result
```


```python
division()
```




    10.0




```python
def division3():
    result=(((6 - 3) + 2 * 4) * 8 / 4)
    return result
```


```python
division3()
```




    22.0




```python
# this is how the division3 fun will work :

# (6 – 3) = 3
# 2 * 4 = 8
# 3 + 8 = 11
# 8 /4 = 2
# 11 * 2 = 22.0
```


```python
def division4():
    p = 1
    q = 2
    if(p > 0 and q > 0):
        return ('p and q are positive integer numbers.')
```


```python
division4()
```




    'p and q are positive integer numbers.'




```python
# Associativity in Python

# Associativity in Python is the order in which the Python interpreter 
# evaluates the expression that contains more than one operator of the same precedence.
```


```python
def division5():
    result1 = 10 * 20 / 10
    result2 = 20 / 10 * 10
    print(result1)
    print(result2)
```


```python
division5()
```

    20.0
    20.0



```python
def division6():
    result1 = (2 ** 2 ** 3) #-->  it first evaluates (2 ** 3) op 8 and then  2 ** 8 op 256
    result2 = (2 ** 2) ** 3 #-->  it first evaluates (2 ** 2) op 4 and then 4 ** 3 op 64
    print(result1)
    print(result2)
```


```python
division6()
```

    256
    64



```python

```


---
**Score: 25**