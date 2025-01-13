---
title: Variables-Python
date: 2025-01-13
author: Your Name
cell_count: 24
score: 20
---

```python
#  created : 20250112
```


```python
#  https://www.scientecheasy.com/2022/09/variables-in-python.html/
```


```python
#  variables in pyhton 

```


```python
num = 20
print(id(num))
```

    8910408



```python
x = 20 
y = 50
z = 100
```


```python
print(x);print(y);print(z)
```

    20
    50
    100



```python
phy = 89
chem = 86
maths = 90

marks_obtained = phy + chem + maths

mark = (marks_obtained * 100) / 300
```


```python
print(mark)
```

    88.33333333333333



```python
x = 80 
y = 99.99
name = 'Radhika'

```


```python
print(x); print(y); print(name);
```

    80
    99.99
    Radhika



```python
radius = 5
pi = 3.14
perimeter = 2 * pi * radius
area = 3.14 * radius * radius
```


```python
print("Perimeter of the circle = ", perimeter)
print("Area of the circle = ", area)
```

    Perimeter of the circle =  31.400000000000002
    Area of the circle =  78.5



```python
#  Multiple Assignment
```


```python
x = y = z = 20
```


```python
print(id(x));print(id(y));print(id(z))
```

    8910408
    8910408
    8910408



```python
x = 20
y = x
z = y
```


```python
print(id(x));print(id(y));print(id(z))
```

    8910408
    8910408
    8910408



```python
 # Assigning multiple values to multiple variables:


```


```python
x, y, z = 20, 25.50, 'text'
```


```python
print(id(x));print(id(y));print(id(z))
```

    8910408
    123760071817712
    8949624



```python
fruit1, fruit2, fruit3 = "Banana", "Orange", "Mango"
```


```python
print(id(fruit1));print(id(fruit2));print(fruit3)
```

    123760050301936
    123760113181616
    Mango



```python
print(type(fruit1))
```

    <class 'str'>



```python

```


---
**Score: 20**