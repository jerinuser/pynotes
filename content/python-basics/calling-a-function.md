---
title: Calling-A-Function
date: 2025-05-17
author: Your Name
cell_count: 34
score: 30
---

```python
#  created : 20250321
```


```python
#  https://www.scientecheasy.com/2022/12/calling-a-function-in-python.html/
```


```python
# Execution Style of Calling a Function in Python
```


```python
# Function definition.
def funct_name(): # function header.
    print('This function does not contain any parameter.')
# Main program execution started from here.
funct_name() # function calling.

```

    This function does not contain any parameter.



```python
# Function definition.
def calcSum(x, y): # Here, x and y are local variables.
    z = x + y # Here, z is a local variable.
    print("Sum of two numbers = ",z)
# Main program.
# Calling a function by passing two argument values.
calcSum(20, 30)

```

    Sum of two numbers =  50



```python
# Calling a Function from Another Function in Python
```


```python
# Function1 to take inputs from the user.
def funct_in():
    num1 = int(input('Enter your first number: '))
    num2 = int(input('Enter your second number: '))
    calcSum(num1, num2) # Calling function2 from function1.
```


```python
# Function2 to calculate the sum of two numbers.
def calcSum(num1, num2):
    sum = num1 + num2
    print("Sum of two numbers = ",sum)
```


```python
# Main part of the program.
funct_in() # calling function1.
```

    Enter your first number:  20
    Enter your second number:  34


    Sum of two numbers =  54



```python
# Examples based on Function Call
# 
```


```python
# Function1 to take the input from the user.
def funct_in():
    length = int(input('Enter the length of rectangle: '))
    breadth = int(input('Enter the breadth of rectangle: '))
    calcPer(length, breadth) # Calling function2 from function1.
    calcArea(length, breadth) # Calling function3 from the function1.
```


```python
# Function2 to calculate the perimeter of rectangle.
def calcPer(l, b):
    per = 2 * (l + b)
    print("Perimeter of the rectangle = ",per)
```


```python
# Function3 to calculate the area of the rectangle.
def calcArea(l, b):
    area = l * b
    print('Area of the rectangle =',area)
```


```python
# Main part of the program.
funct_in() # calling function1.
```

    Enter the length of rectangle:  4
    Enter the breadth of rectangle:  4


    Perimeter of the rectangle =  16
    Area of the rectangle = 16



```python
# Example 2:
```


```python
# Function1 to calculate addition of two numbers.
def add(x, y):
    z = x + y
    print("Addition:",z)
```


```python
# Function2 to calculate the subtraction.
def sub(p, q):
    r = p - q
    print("Subtraction:",r)

```


```python
# Function3 to calculate the multiplication.
def multiply(a, b):
    c = a * b
    print('Multiplication:',c)
```


```python
# Function4 to calculate the division.
def div(n, m):
    d = n / m
    print('Division:',d)
```


```python
# Function5 to take inputs from the user and calling.
def main_funct():
    n1 = int(input('Enter your first number: '))
    n2 = int(input('Enter your second number: '))
    add(n1, n2)
    sub(n1, n2)
    multiply(n1, n2)
    div(n1, n2)
```


```python
# Main program.
main_funct() # calling function5.
```

    Enter your first number:  10
    Enter your second number:  20


    Addition: 30
    Subtraction: -10
    Multiplication: 200
    Division: 0.5



```python
# Example 3:
```


```python
def square(num):
    result = num * num
    print("Square of",num,"=",result)
square(5)
```

    Square of 5 = 25



```python
# Example 4:
```


```python
# Python program to swap two numbers.
def swap(x, y):
    print('Before swapping: ')
    print('x:',x)
    print('y:',y)
    temp = x
    x = y
    y = temp
    print('After swapping: ')
    print('x:',x)
    print('y:',y)
```


```python
# Calling function with passing two arguments.
swap(20, 10)
```

    Before swapping: 
    x: 20
    y: 10
    After swapping: 
    x: 10
    y: 20



```python
# Example 5:
```


```python
# Python program to check a number is even or odd.
num = int(input('Enter your number to check even or odd: '))
# Create a function.
def evenorodd():
    if num % 2 == 0:
        print(num,'is an even number.')
    else:
        print(num,'is an odd number.')
# Calling function.
evenorodd()
```

    Enter your number to check even or odd:  2


    2 is an even number.



```python
# Python program to check a year is leap or not.
year = int(input('Enter a year: '))
def leap():
    if year % 4 == 0 and year % 100 != 0 or year % 400 == 0:
        print(year,'is a leap year.')
    else:
        print(year,'is not a leap year.')
# Calling function.
leap()
```

    Enter a year:  2025


    2025 is not a leap year.



```python
# Some More Example Program for Practice
```


```python
# Python program to check a number is prime or not.
# Create a function to check conditions for the prime.
def primeChecker(n):
    # Using if-else statement for checking the number is greater than 1.
    if n > 1:
        # Iterating over the number using for loop.
        for x in range(2, int(n/2) + 1):
            # Check the number is divisible or not.
            if (n % x) == 0:
                print(n, "is not a prime number.")
                break
           # Else part if it is a prime number.
            else:
                print(n, "is a prime number.")
    # Else part if the number is not greater than 1.
    else:
        print(x, "is not a prime number")

# Main part of the program.
# Take a number as input from the user.
n = int(input("Enter a number to check prime or not: "))
# Calling function with passing input number.
primeChecker(n)
```

    Enter a number to check prime or not:  90


    90 is not a prime number.



```python
def sqList():
  # Creating an empty list that will hold values.
    l = list()
    for x in range(1, 11):
        l.append(x ** 2)
    print(l)
# Function call.
sqList()

```

    [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]



```python
def totalMarks():
  # Marks of five subjects for a student.
    marks = [68, 98, 78, 88, 86]
  # Transferring individual marks into independent variable.
    m1 = marks[0]
    m2 = marks[1]
    m3 = marks[2]
    m4 = marks[3]
    m5 = marks[4]
  # Total marks.
    totMarks = m1 + m2 + m3 + m4 + m5
    print('Total marks obtained:',totMarks)
  # Percentage.
    per = totMarks / 5
    print('Percentage:',per)
# Function call.
totalMarks()

```

    Total marks obtained: 418
    Percentage: 83.6



```python

```


---
**Score: 30**