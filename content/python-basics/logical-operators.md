---
title: Logical-Operators
date: 2025-05-17
author: Your Name
cell_count: 52
score: 50
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/logical-operators-in-python.html/
```


```python
#  x > y and y > z # Two relational expressions combined by a logical and operator.
```


```python
#  Types of Logical or Boolean Operators in Python
# and
#  or 
#  not
```


```python
# Logical AND Operator
```


```python
x, y = 10, 5
result = (x == 10 and y == 5) 
```


```python
print(result)

```

    True



```python
result = (x == 10 and y > x)
print(result)
```

    False



```python
result = (x < y and y > x)
print(result)
```

    False



```python
x, y, z = 20, 10, 25
```


```python

```


```python
if(x > y and y > z):
    print("Hello")
if(z > y and y < x):
    print("Python")
if((y+200) < x and (y+150) < z):
    print("Hello Python")
```

    Python



```python
x = (15 < 20) and ("pen" < "pencil")
y = ("Big" < "bigger") and (True != 1)
z = ("A" <= "A") and ("a" != "a")
print("x: ", x)
print("y: ", y)
print("z: ", z)

```

    x:  True
    y:  False
    z:  False



```python
p = True and True
q = False and True
r = 'a' and 'b'
s = False and 'a'
t = 'a' and True
```


```python
print("p: ", p)
print("q: ", q)
print("r: ", r)
print("s: ", s)
print("t: ", t)
```

    p:  True
    q:  False
    r:  b
    s:  False
    t:  True



```python
p = (True == 1) and (False == 0)
q = ("2" != 2) and (2 == 2)
r = ("5+5" == 5+5) and True
s = (False == 0) and (5 > 2)
t = (10 + True >= 10) and False
```


```python
print("p: ", p)
print("q: ", q)
print("r: ", r)
print("s: ", s)
print("t: ", t)
```

    p:  True
    q:  True
    r:  False
    s:  True
    t:  False



```python
#  Logical OR Operator
```


```python
print((2 == 2) or (3 > 5))
```

    True



```python
print((5 > 18) or (3 != 9))
```

    True



```python
print((4 == 4) or (5 < 9))
```

    True



```python
print((4 < 2) or (2 == 1))
```

    False



```python
print((3 != 3) or (3 >= 9))
```

    False



```python
x, y, z = 20, 10, 5
```


```python
if(x > y or y > z):
    print("Python")
```

    Python



```python
if(z > y or y < x):
    print("JavaScript")
```

    JavaScript



```python
if((y+20) < x or (z+15) < y):
    print("Java")
else: 
    print("No java")
```

    No java



```python
x, y, z = 10, 5, 20
```


```python
if((x > y) or ( y == z)):
    print("One")
```

    One



```python
if((x == y) or (y < z )):
    print("Two")
```

    Two



```python
if((x != y) or (y != z)):
    print("Three")
```

    Three



```python
if((x < y) or (y > z)):
    print("Four")
```


```python
a = ("big " != "bigger") or False
print("a: ", a)
```

    a:  True



```python
b = True or False
print("b: ", b)

```

    b:  True



```python
c = "a" or D
print("c: ", c)
```

    c:  a



```python
d = ("ABc" > "abC") or False
print("d: ", d)
```

    d:  False



```python
p = (True == 1) or (False == 0)
q = ("2" != 2) or (2 == 2)
r = ("5+5" == 5+5) or False
s = (False == 0) or (5 > 2)
t = (10 >= True) or False
```


```python
print("p: ", p)
print("q: ", q)
print("r: ", r)
print("s: ", s)
print("t: ", t)
```

    p:  True
    q:  True
    r:  False
    s:  True
    t:  True



```python
#  Logical NOT Operator
```


```python
if(not(2 > 5)):
    print("I love Python Programming")
```

    I love Python Programming



```python
print(not(5 == 5))
```

    False



```python
print(not(False)) 
```

    True



```python
print(not(True)) 
```

    False



```python
#  Example Program based on Logical NOT Operator

```


```python
a = not("ABc" > "ABC") or False
print("a: ", a)
```

    a:  False



```python
b = not(True) or not(False)
print("b: ", b)
```

    b:  True



```python
c = (True >= 0) or not(20 == 20)
print("c: ", c)
```

    c:  True



```python
d = not("5" == 10) and not(False and (10 != 20))
print("d: ", d)
```

    d:  True



```python
a = not("abc" < "ABCD") and not(False)
print("a: ", a)

```

    a:  True



```python
b = not True and not False
print("b: ", b)

```

    b:  False



```python
c = not("20" == 20) and not(True == False)
print("c: ", c)
```

    c:  True



```python

```


---
**Score: 50**