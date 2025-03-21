---
title: Assignment-Operators
date: 2025-03-21
author: Your Name
cell_count: 44
score: 40
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/assignment-operators-in-python.html/
```


```python
# Assignment Operators in Python
```


```python
# Simple Assignment
```


```python
x = 20
y = 50
z = x + y + 2
```


```python
print("Result = ", z)
```

    Result =  72



```python
# x += y  It is equivalent to x = x + y.
```


```python
x = 20
y = 5
z = 10
x += y
```


```python
print("Result of (x = x + y) = ", x)
```

    Result of (x = x + y) =  25



```python
z += x + y
print("Result = ", z)
```

    Result =  40



```python
x -= y # It is equivalent to x = x - y.
```


```python
x = 20
y = 5
z = 10
x -= y
print("Result of (x = x - y) = ", x)
```

    Result of (x = x - y) =  15



```python
z -= x + y # --> z = z - (x + y)
print("Result = ", z)
```

    Result =  -10



```python
x *= y # It is equivalent to x = x * y.
```


```python
x = 2
y = 5
z = 3
x *= y

```


```python
print("Result of (x = x * y) = ", x)
```

    Result of (x = x * y) =  10



```python
z *= x * y
```


```python
print("Result of (z = z*(x * y) = ", z)
```

    Result of (z = z*(x * y) =  150



```python
x /= y # It is equivalent to x = x / y.

```


```python
x = 20
y = 5
z = 100
x /= y
```


```python
print("Result of (x = x / y) = ", x)
```

    Result of (x = x / y) =  4.0



```python
z /= x * y
print("Result = ", z)
```

    Result =  5.0



```python
x %= y # It is equivalent to x = x % y.
```


```python
x = 211
y = 5
z = 100
x %= y
```


```python
print("Result of (x = x % y) = ", x)
```

    Result of (x = x % y) =  1



```python
z %= x + y
```


```python
print("Result = ", z)
```

    Result =  4



```python
x //= y # It's equivalent to x = x // y.
```


```python
x = 211
y = 5
z = 100
x //= y
print("Result of (x = x // y) = ", x)
```

    Result of (x = x // y) =  42



```python
z //= x + y
print("Result = ", z)
```

    Result =  2



```python
x = 211
y = 5
z = 100
x //= y

print("Result of (x = x // y) = ", x)

z //= x + y
print("Result = ", z)

```

    Result of (x = x // y) =  42
    Result =  2



```python
#  Exponent and Assignment Operator (**=)
```


```python
x **= y # It's equivalent to x = x ** y.
```


```python
x = 2
y = 5
z = 2
x **= y

print("Result of (x = x ** y) = ", x)

z **= x + y - 30
print("Result = ", z)
```

    Result of (x = x ** y) =  32
    Result =  128



```python
# Bitwise AND and Assignment Operator (&=)
```


```python
x &= y # It's equivalent to x = x & y.
```


```python
x = 20
y = 5
x &= y
print("Result of (x = x & y) = ", x)
```

    Result of (x = x & y) =  4



```python
#  Bitwise OR and Assignment Operator (|=)
```


```python
x |= y # It's equivalent to x = x | y.
```


```python
x = 10
y = 5
x |= y
print("Result of (x = x | y) = ", x)
```

    Result of (x = x | y) =  15



```python
# Bitwise XOR and Assignment Operator (^=)
```


```python
x ^= y # It's equivalent to x = x ^ y.
```


```python
x = 20
y = 10
x ^= y
print("Result of (x = x ^ y) = ", x)
```

    Result of (x = x ^ y) =  30



```python

```


---
**Score: 40**