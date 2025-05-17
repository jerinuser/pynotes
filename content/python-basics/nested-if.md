---
title: Nested-If
date: 2025-05-17
author: Your Name
cell_count: 15
score: 15
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/python-nested-if.html/
```


```python

```


```python
x = 20
y = 10
z = 5
# Outer if statement.
if x > y:
    if y > z: # Nested inner if statement.
        print('Hello')
```

    Hello



```python
x = 20
y = 10
z = 5
# Outer if statement.
if x > y:
    if y < z: # Nested inner if statement.
        print('Hello')
    print('Hi')
```

    Hi



```python
x = 20
y = 10
z = 5
# Outer if statement.
if x < y: 
    if y > z: # Nested inner if statement.
        print('Hello')
    print('Hi')
```


```python
# Nested If else Statement in Python

```


```python
x = 20
y = 10
z = 5
# Outer if else statement.
if x > y:
    print('Outer if block')
    if y < z: # Nested inner if else statement.
        print('Inner if block')
    else:
        print('Inner else block')
else:
    print('Outer else block')
```

    Outer if block
    Inner else block



```python
# Take a number as input from the user.
num = int(input('Enter a number that you want to check divisible: '))
# Outer if else statement.
if num % 2 == 0:
    if num % 3 == 0: # Nested inner if else statement.
        print('The number is divisible by 2 and 3.')
    else:
        print('The number is divisible by 2, but not divisible by 3.')
else:
    if num % 3 == 0:
        print('The number is divisible by 3, but not divisible by 2')
    else:
        print('The number is not divisible 2 and 3.')
```

    Enter a number that you want to check divisible:  34


    The number is divisible by 2, but not divisible by 3.



```python
num = int(input('Enter a number that you want to check: '))
# Outer if else statement.
if num >= 0:
    if num == 0: # Nested inner if else statement.
        print('Number is zero.')
    else:
        print('Number is positive.')
else:
    print('Number is negative.')
```

    Enter a number that you want to check:  23


    Number is positive.



```python
age = int(input('Please enter your age: '))
# Outer if else statement.
if age < 18:
    print('You are minor and not eligible to cast vote.') 
else: 
    if age >= 18 and age < 60:
        print('You are young and eligible to cast vote')
    else:
        print('You are a senior citizen person and will be given special care to cast vote.')
```

    Please enter your age:  22


    You are young and eligible to cast vote



```python
# Program to check a year is leap year or not.
year = int(input('Please enter a year: '))
if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print(year,'is a leap year.')
        else:
            print(year,'is not a leap year.')
    else:
        print(year,'is a leap year.')
else:
    print(year, 'is not a leap year.')
```

    Please enter a year:  2025


    2025 is not a leap year.



```python
# Nested If-elif-else Statement in Python

```


```python
# Program to make a simple mathematical calculator.
opr = input('Please enter an operator [+, -, *, or /]: ')
if(opr == '+' or opr == '-' or opr == '*' or opr == '/'):
    n1 = int(input('Please enter your first number: '))
    n2 = int(input('Please enter your second number: '))
    if(opr == '+'):
        sum = n1 + n2
        print("Sum of",n1,'and', n2,'=', sum)
    elif(opr == '-'):
        if(n1 > n2):
            diff = n1 - n2
        else:
            diff = n2 - n1
        print('Difference between',n1,'and',n2,'=', diff)
    elif(opr == '*'):
        multiply = n1 * n2
        print('Multiplication of',n1,'and',n2,'=', multiply)
    elif(opr == '/'):
        if(n1 == 0 or n2 == 0):
            print('Numbers must be positive.')
        else:
            div = n1 / n2
            print('Division of',n1,'by',n2,'=', div)
else:
    print('Sorry, you have entered an invalid operator. Please choose any of these +, -, *, or /.')
```

    Please enter an operator [+, -, *, or /]:  -
    Please enter your first number:  2
    Please enter your second number:  3


    Difference between 2 and 3 = 1



```python

```


---
**Score: 15**