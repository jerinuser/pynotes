---
title: Comparison-Operators
date: 2025-01-13
author: Your Name
cell_count: 50
score: 50
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/comparison-operators-in-python.html/
```


```python
#  Comparison  Operators
```


```python
# Equal to (==)

```


```python
x = 20
y = 20
print( x == y)
```

    True



```python
p = 'My name is John'
q = 'My name is John'
print( p == q)
```

    True



```python
r = 'Text'
s = 'text'
print( r == s)
```

    False



```python
t = [1, 2, 3, 4]
u = [1, 2, 3]
print( t == u)
```

    False



```python
List1 = [10, 20, 30, 40, 50]
List2 = List1
print( List1 == List2)
```

    True



```python
x = 50.0
y = 50
print(x == y)
```

    True



```python
str1 = 'My name is John'
str2 = str1
print(str1 == str2)

```

    True



```python
a = True
b = 1
print(a == b)
```

    True



```python
#   Not equal to (!=)
```


```python
x = 50
y = 90
print( x != y)
```

    True



```python
str1 = 'My name is John'
str2 = str1
print( str1 != str2)
```

    False



```python
a = True
b = 1
print( a != b)

```

    False



```python
p = False
q = 0
print( p != q)

```

    False



```python
r = '50'
s = 50
print( r != s)
```

    True



```python
List1 = [10, 20, 'Python', '30']
List2 = [10, 20, 'Python', 30]
```


```python
print(List1 != List2)
```

    True



```python
Dict1 = {
     1: 'a',
     2: '20'
}
Dict2 = {
    1: 'a',
    2: '20'
}
```


```python
print(Dict1 != Dict2)
```

    False



```python
#  Greater than (>)

```


```python
num1 = 60
num2 = 50


print(num1 > num2)
print(num1 + 20 - 20 > num2 + 20)
```

    True
    False



```python
n1 = 20
n2 = n1


print(n1 > n2)
```

    False



```python
str1 = 'Python' # --> considered by len
str2 = 'Pythe'


print(str1 > str2)
```

    True



```python
str1 = 'Python' #--> different data type will raise a error 
str2 = 20
print(str1 > str2)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[37], line 3
          1 str1 = 'Python' #--> different data type will raise a error 
          2 str2 = 20
    ----> 3 print(str1 > str2)


    TypeError: '>' not supported between instances of 'str' and 'int'



```python
str1 = 'Python'
str2 = '20'
print(str1 > str2)

```

    True



```python
p = True
q = 2
print(q > p)
```

    True



```python
r = False
s = -1
print(r > s)
```

    True



```python
List1 = [10, 20, 30]
List2 = [10, 20, 40]
print(List1 > List2)
```

    False



```python
#  Less than (<)
```


```python
num1 = 20
num2 = 20.05
print(num1 < num2)
```

    True



```python
exp1 = 20 * 20 % 20
exp2 = 20 + 20 / 20
print(exp2 < exp1)
```

    False



```python
str1 = 'Python'
str2 = 'Text'
print(str1 < str2)
```

    True



```python
p = True
q = 0
print(q < p)
```

    True



```python
r = False
s = -2
print(r < s)
```

    False



```python
List1 = [1, 2, 3]
List2 = [1, 2, 4]
print(List1 < List2)
```

    True



```python
# Greater than or equal to (>=)

```


```python
num1 = 20.20
num2 = 20.0200
print(num1 >= num2)
```

    True



```python

x = True + 2
y = False + False + False

print(x >= y)
```

    True



```python
p = 'abcd'
q = 'abcde'

print(p >= q)
```

    False



```python
#  Less than or equal to (<=)

```


```python
num1 = 40.40
num2 = 40.400
print(num1 <= num2)

```

    True



```python
x = True + 2
y = False + False + False
print(x <= y)
```

    False



```python
p = 'A'
q = 'B'
print(p <= q)
```

    True



```python
# Use of Comparison Operators in Decision Making Statement

```


```python
# Program to illustrate the use of comparison or relational operators. 
p = 50
q = 60
if(p == q):
    print("p is equal to q")
else:
    print("p is not equal to q")
if(p != q):
    print("p is not equal to q")
else:
    print("p is equal to q")
if(p > q):
    print("p is greater than q")
else:
    print("p is not greater than q")
if(p < q): print("p is less than q") 
else: 
    print("p is not less than q")
if(p >= q):
    print("p is greater than or equal to q")
else:
    print("p is not greater than or equal to q")
if(p <= q):
    print("p is less than or equal to q")
else:
    print("p is not less than or equal to q")

```

    p is not equal to q
    p is not equal to q
    p is not greater than q
    p is less than q
    p is not greater than or equal to q
    p is less than or equal to q



```python
age = int(input("Enter your age: "))
if(age >= 18):
    print("You are eligible for voting.")
else:
    print("You are not eligible for voting.")
```

    Enter your age:  23


    You are eligible for voting.



```python

```


---
**Score: 50**