---
title: Ternary-Operator
date: 2025-01-13
author: Your Name
cell_count: 13
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/ternary-operator-in-python.html/
```


```python
#  Ternary Operator in Python
```


```python
x =  10 
y = 20 


if(x > y):
    msg = 'Hello'
else:
    msg = 'Goodbye'
```


```python
print('Hello' if True else 'Goodbye') 
print('Hello' if False else 'Goodbye') 
```

    Hello
    Goodbye



```python
x, y = 20, 40
z = 20 if (x > y) else 40
print("Greatest number: ", z)
```

    Greatest number:  40



```python
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
num3 = int(input("Enter the third number: "))
greatest_num = (num1 if (num1 > num3) else num3) if (num1 > num2) else (num2 if (num2 > num3) else num3)
print('The greatest number among three numbers: ', str(greatest_num))
```

    Enter the first number:  20
    Enter the second number:  30
    Enter the third number:  40


    The greatest number among three numbers:  40



```python
age = int(input("How old are you?"))
eligible = "You are eligible to vote." if (age >= 18) else "You are not eligible to vote."
print(eligible)
```

    How old are you? 23


    You are eligible to vote.



```python
total = 0;
yearCheck = int(input("Enter a year: "))

check4 = 1 if (yearCheck % 4 == 0) else 0
check100 = -1 if (yearCheck % 100 == 0) else 0
check400 = 1 if (yearCheck % 400 == 0) else 0

total = check4 + check100 + check400

print("Leap year" if(total == 1) else "Not leap year")
```

    Enter a year:  24


    Leap year



```python
num1 = int(input('Enter your first number: '))
num2 = int(input('Enter your second number: '))
print(num1, "is greater number") if (num1 > num2) else print(num2, "is greater number")
```

    Enter your first number:  22
    Enter your second number:  11


    22 is greater number



```python
# Nested Ternary Operator
```


```python
num1, num2 = 10, 20
# Nested ternary operator.
num = "num1 = num2" if(num1 == num2) else "num1 > num2" if(num1 > num2) else "num2 > num1"
print(num)
```

    num2 > num1



```python

```


---
**Score: 10**