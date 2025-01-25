---
title: If-Else
date: 2025-01-25
author: Your Name
cell_count: 21
score: 20
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/if-else-in-python.html/
```


```python
def num():
    num = int(input("enter the num:"))
    if num % 2 == 0:
        print(num, "is divisible by 2.")
    else:
        print(num, "is not divisible by 2.")
```


```python
num()
```

    enter the num: 8


    8 is divisible by 2.



```python
def marks():
    passMarks = int(input("enter your mark:"))
    if passMarks >= 40:
        print("Passed")
    else:
        print("Failed")
```


```python
marks()
```

    enter your mark: 65


    Passed



```python
marks()
```

    enter your mark: 39


    Failed



```python
def example():
    x, y = 20, 40
    if x > y:
        print(x, "is greater than ",y)
    else:
        print(y, "is greater than ", x)
```


```python
example()
```

    40 is greater than  20



```python
def gender():
    gender = 'M'
    if((gender == 'M') or (gender == 'm')):
        print("You are a male")
    else:
        print("You are a female")
```


```python
gender()
```

    You are a male



```python
def number():
    
    number = int(input('Enter a number: '))
    if number % 2 == 0:
        print(number, "is an even number.")
    else:
        print(number, "is an odd number.")
```


```python
number()
```

    Enter a number:  90


    90 is an even number.



```python
def marks():
    
    chem = int(input('Enter your chemistry marks: '))
    phy = int(input('Enter your physics marks: '))
    maths = int(input('Enter your maths marks: '))
    
    total = chem + phy + maths
    per = total / 3
    print("Total marks obtained: ", total)
    print("Percentage: ", per)
    
    if per >= 85:
        print("Grade A")
    else:
        print("Grade B")
```


```python
marks()
```

    Enter your chemistry marks:  40
    Enter your physics marks:  90
    Enter your maths marks:  100


    Total marks obtained:  230
    Percentage:  76.66666666666667
    Grade B



```python
# A number is a buzz number when it ends with 7 or is divisible by 7.

```


```python
def buzz():
        
    num = int(input('Enter an integer number to check buzz: '))
    if (num % 10 == 0) or (num % 7 == 0):
        print(num, "is a Buzz number")
    else:
        print(num, "is not a Buzz number")
```


```python
buzz()
```

    Enter an integer number to check buzz:  776


    776 is not a Buzz number



```python
def salary():
        
    salary = 7500
    if salary >= 8000:
        salary = salary + (salary * 0.1)
        print("Employee salary: ", salary)
    else:
        salary = salary + (salary * 0.15)
        print("Employee salary: ", salary)
```


```python
salary()
```

    Employee salary:  8625.0



```python

```


---
**Score: 20**