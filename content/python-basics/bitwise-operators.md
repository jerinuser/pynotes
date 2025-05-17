---
title: Bitwise-Operators
date: 2025-05-17
author: Your Name
cell_count: 49
score: 45
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/bitwise-operators-in-python.html/
#  https://chatgpt.com/share/678524a9-cd24-8012-a475-2b7098cd8750
```


```python
# Bitwise Operators in Python
```


```python
# &	    Bitwise AND	                Binary
# |	    Bitwise OR	                Binary
# ^	    Bitwise XOR (Exclusive OR)	Binary
# ~	    Bitwise NOT	                Unary
# <<	Bitwise Left Shift	        Binary
# >>	Bitwise Right Shift      	Binary
```


```python
# Bitwise AND operator (&)
```


```python
A = 2
B = 6
result = A & B
```


```python
print("Result of (2 & 6): ", result)
```

    Result of (2 & 6):  2



```python
A = 25
B = 45
result = A & B
```


```python
print("Result of (25 & 45): ", result)
```

    Result of (25 & 45):  9



```python
A = -25
B = 45
result = A & B
```


```python
print("Result of (-25 & 45): ", result)

```

    Result of (-25 & 45):  37



```python
X = True
Y = 45
result = X & Y
```


```python
print("Result of (True & 10): ", result)
```

    Result of (True & 10):  1



```python
P = False
Q = 15
result = P & Q
```


```python
print("Result of (False & 20): ", result)
```

    Result of (False & 20):  0



```python
# Bitwise OR operator (|)

```


```python
A = 2
B = 6
result = A | B
```


```python
print("Result of (2 | 6): ", result)
```

    Result of (2 | 6):  6



```python
A = 25
B = 45
result = A | B
```


```python
print("Result of (25 | 45): ", result)
```

    Result of (25 | 45):  61



```python
A = -25
B = 45
result = A | B
```


```python
print("Result of (-25 | 45): ", result)

```

    Result of (-25 | 45):  -17



```python
X = True
Y = 45
result = X | Y
```


```python
print("Result of (True | 10): ", result)
```

    Result of (True | 10):  45



```python
P = False
Q = 15
result = P | Q
```


```python
print("Result of (False | 20): ", result)
```

    Result of (False | 20):  15



```python
# Bitwise XOR operator (^)

```


```python
A = 2
B = 6
result = A ^ B
```


```python
print("Result of (A ^ B): ", result)
```

    Result of (A ^ B):  4



```python
A = 25
B = 45
result = A ^ B

```


```python
print("Result of (25 ^ 45): ", result)
```

    Result of (25 ^ 45):  52



```python
X = True
Y = 45
result = X ^ Y
```


```python
print("Result of (True ^ 10): ", result)

```

    Result of (True ^ 10):  44



```python
P = False
Q = 15
result = P ^ Q
```


```python
print("Result of (False ^ 20): ", result)
```

    Result of (False ^ 20):  15



```python
# Bitwise NOT operator (~)

```


```python
A = 3
B = 1
result = A << B
```


```python
print("Result of (A << B): ", result)

```

    Result of (A << B):  6



```python
X = 3
Y = 2
result = X << Y
```


```python
print("Result of (X << Y): ", result)
```

    Result of (X << Y):  12



```python
X = 25
Y = 2
result = X << Y
```


```python
print("Result of (A << B): ", result)
```

    Result of (A << B):  100



```python
# Bitwise Right Shift Operator (>>)

```


```python
A = 6
B = 1
result = A >> B
```


```python
print("Result of (A >> B): ", result)
```

    Result of (A >> B):  3



```python
X = 6
Y = 2
result = X >> Y
```


```python
print("Result of (X >> Y): ", result)
```

    Result of (X >> Y):  1



```python
p = int(input('Enter your first number: '))
q = int(input('Enter your second number: '))
r = int(input('Enter the number of bits to be shifted towards left and right: '))

print('Outcome of bitwise &: ', p & q)
print('Outcome of bitwise |: ', p | q)

print('Outcome of bitwise ^: ', p ^ q)
print('Outcome of bitwise ~: ', ~p)

print('Outcome of bitwise ~: ', ~q)
print('Outcome of bitwise <<: ', p << r) ;print('Outcome of bitwise >>: ', p >> r)

```

    Enter your first number:  1
    Enter your second number:  2
    Enter the number of bits to be shifted towards left and right:  3


    Outcome of bitwise &:  0
    Outcome of bitwise |:  3
    Outcome of bitwise ^:  3
    Outcome of bitwise ~:  -2
    Outcome of bitwise ~:  -3
    Outcome of bitwise <<:  8
    Outcome of bitwise >>:  0



```python

```


---
**Score: 45**