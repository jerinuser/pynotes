---
title: Reversed-Keyword
date: 2025-01-25
author: Your Name
cell_count: 22
score: 20
---

```python
#  created : 20250111
```


```python
#  https://www.scientecheasy.com/2022/09/reserved-keywords-in-python.html/
```


```python
import keyword

```


```python
print(keyword.kwlist)
```

    ['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']



```python
#  Description of Keywords in Python with Examples

```


```python
print( 5 == 5 )
print( 10 > 9 )
print( True or False )
print( 9 <= 28 )
```

    True
    True
    True
    True



```python
print( True == 1 )
print( True + True + True)
```

    True
    3



```python
print(10 > 20)
print(50 <= 30)
print(False == 1)
print(False == 0)
print(False + False + 1) 
```

    False
    False
    False
    True
    1



```python
print(None == False)
print( None == 0 )
print( None == " " )
```

    False
    False
    False



```python
A = None
B = None
C = None
```


```python
print( A == B )
print( B == C )
print( A == C )
```

    True
    True
    True



```python
print(True and True)
print(True and False and True)
print(True and 1)
```

    True
    False
    1



```python
print(True or True)
print(False or False or True)
print(True or False)
print(True or 1)
```

    True
    True
    True
    True



```python
print(not True)
print(not False)
```

    False
    True



```python
num = [10, 20, 30, 40, 50]
```


```python
print(15 not in num)
```

    True



```python
print(50 in num)
```

    True



```python
for i in 'keyword':
     print(i)
```

    k
    e
    y
    w
    o
    r
    d



```python
print( True is True )
print( False is True )
print( None is None )
print((2 + 4) is (3 * 2))
```

    True
    False
    True
    True


    <>:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
    <>:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
    /tmp/ipykernel_17126/3779890185.py:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
      print((2 + 4) is (3 * 2))



```python
print( [ ] == [ ] )
print( [ ] is [ ] )  
print( { } == { } )
print( { } is { } )
```

    True
    False
    True
    False



```python
print( ' ' == ' ' )
print( ' ' is ' ' )
print( () == () )
print( () is () )
```

    True
    True
    True
    True


    <>:2: SyntaxWarning: "is" with a literal. Did you mean "=="?
    <>:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
    <>:2: SyntaxWarning: "is" with a literal. Did you mean "=="?
    <>:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
    /tmp/ipykernel_17126/3115633758.py:2: SyntaxWarning: "is" with a literal. Did you mean "=="?
      print( ' ' is ' ' )
    /tmp/ipykernel_17126/3115633758.py:4: SyntaxWarning: "is" with a literal. Did you mean "=="?
      print( () is () )



```python

```


---
**Score: 20**