---
title: Expression
date: 2025-03-16
author: Your Name
cell_count: 10
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/expression-in-python.html/
```


```python
#  Arithmetic Expression
```


```python
num1 = 20
num2 = 40
sum = num1 + num2 # An arithmetic expression.
print("Sum of two numbers is ", sum)
```

    Sum of two numbers is  60



```python
# Relational/Conditional Expression
```


```python
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
num3 = int(input("Enter the third number: "))

if num1 > num2 and num1 > num3:
    print(num1, 'is a greater number among the three numbers.')
elif num2 > num1 and num2 > num3:
    print(num2, 'is a greater number among the three numbers.')
else:
    print(num3, 'is a greater number among the three numbers.')

```

    Enter the first number:  32
    Enter the second number:  23
    Enter the third number:  12


    32 is a greater number among the three numbers.



```python
Age = int(input("Enter your age: "))
if Age >= 18:
    print('You can cast vote.')
else:
    print('You cannot cast vote.')
```

    Enter your age:  32


    You can cast vote.



```python
# Logical Expression
```


```python
p = 10
q = 15
r = 5
s = 20
result = p > q and r > s
print("Logical expression (p > q and r > s) returns ", result)
```

    Logical expression (p > q and r > s) returns  False



```python

```


---
**Score: 10**