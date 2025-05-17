---
title: If-Statement
date: 2025-05-17
author: Your Name
cell_count: 21
score: 20
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/if-statement-in-python.html/
```


```python
# Syntax of if Statement in Python

```


```python
# if test_condition:
#     Python statement(s) to be executed if condition is true.
# or,
# if(test_condition):
#     statement(s)
```


```python
def per():
    myPer = 92
    if myPer >= 80:
        print("Grade A")
```


```python
per()
```

    Grade A



```python
def check():
    if(True): # Here, we have used a boolean value True to check whether the condition is true or not.
        print("Code to be executed") # It will print statement. 
    
    if(False): 
        print("Code not to be executed") # It will not print statement.
```


```python
check()
```

    Code to be executed



```python
def valid():
    x = 1
    if x > 0:
        return(x, " is a positive number")
    
    y = 10
    if(y): # same as: if(x != 0)
        return(y, " is a nonzero number");
    
    a, b = 10, 10
    if(a == b):
        return("x and y are equal number")
    
    c, d = 5, 10
    if c < d:
        return("x is less than y")
    
    f = True
    if(f): # Here, we have used a boolean value to check whether the condition is true or not.
        return("You are eligible to cast vote")
```


```python
valid()
```




    (1, ' is a positive number')




```python
def example():
    radius = 2.5
    pi = 3.14
    if radius >= 0:
        area = radius * radius * pi
        print("Area of circle: ", area)
```


```python
example()
```

    Area of circle:  19.625



```python
def example2():
    num=int(input("enter a number to check if a number is divisible by 2 or not: "))

    if num % 2 == 0:
        print(f"yes the number: {num} is divisible by 2")
    else:
        print(f"no the number: {num} is not divisible by 2")
```


```python
example2()
```

    enter a number to check if a number is divisible by 2 or not:  4


    yes the number: 4 is divisible by 2



```python
def vote():
    age = int(input("Enter your age to check you are eligible to cast a vote or not: "))
    if age >= 18:
        print("You are eligible to cast a vote.")
    
    if age < 18:
        print("You are not eligible to cast a vote")
```


```python
vote()
```

    Enter your age to check you are eligible to cast a vote or not:  23


    You are eligible to cast a vote.



```python
def marks():
    # Prompt the user to enter marks of three subjects.
    phy = int(input("Enter your physics marks: "))
    chem = int(input("Enter your chemistry marks: "))
    maths = int(input("Enter your math marks: "))
    totalMarks = phy + chem + maths
    
    myPer = totalMarks / 3
    print("Total marks obtained: ", totalMarks)
    print("Your percentage: ", myPer)
    
    if(myPer >= 90.0): # if the condition is true, then the statement will be displayed.
        print("Grade A")
    if(myPer < 90.0): # if the condition is true, then the statement will be displayed.
        print("Grade B")
```


```python
marks()
```

    Enter your physics marks:  35
    Enter your chemistry marks:  35
    Enter your math marks:  35


    Total marks obtained:  105
    Your percentage:  35.0
    Grade B



```python
def even_or_odd():
    # Read the number from the user to check even or odd.
    num = int(input("Enter a number: "))
    if num % 2 == 0:
        print(num, 'is an even number')
    if num % 2 != 0:
        print(num, 'is a odd number')
```


```python
even_or_odd()
```

    Enter a number:  5


    5 is a odd number



```python

```


---
**Score: 20**