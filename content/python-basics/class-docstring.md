---
title: Class-Docstring
date: 2025-01-25
author: Your Name
cell_count: 11
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/09/docstring-in-python.html/
```


```python
#  class docstring
```


```python
class Rectangle:
    """
    This is a class for calculating the area of a rectangle.

        Parameters:
        l (int) : The length of rectangle.
        b (int) : The breadth of rectangle.
    """
print(Rectangle.__doc__)
```

    
        This is a class for calculating the area of a rectangle.
    
            Parameters:
            l (int) : The length of rectangle.
            b (int) : The breadth of rectangle.
        



```python
# We can also read docstring using the syntax help()
```


```python
def get_square(x):
    "This is a method for calculating the square of a number."
    return x * x # It will calculate the square of a number and return the output.
help(get_square)
```

    Help on function get_square in module __main__:
    
    get_square(x)
        This is a method for calculating the square of a number.
    



```python
get_square(5)
```




    25




```python
def num(a,b):
    return a*b

```


```python
num(10,90)
```




    900




```python
help(num)
```

    Help on function num in module __main__:
    
    num(a, b)
    



```python

```


---
**Score: 10**