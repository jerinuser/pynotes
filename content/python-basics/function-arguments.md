---
title: Function-Arguments
date: 2025-03-21
author: Your Name
cell_count: 23
score: 20
---

```python
#  created : 20250321
```


```python
#  https://www.scientecheasy.com/2022/12/arguments-in-python.html/
```


```python
# Default Arguments in Python
```


```python
def studentInfo(name, gender = 'Male'):
# This function displays the student's info passed in the function parameters.
    print('Name:',name)
    print('Gender:',gender)
```


```python
# Main program.
# Function call 1.
studentInfo('Deepak')
# Function call 2.
studentInfo('Tripti', gender = 'Female')
```

    Name: Deepak
    Gender: Male
    Name: Tripti
    Gender: Female



```python
def studentInfo(name, rollNo = 20, branch = 'Electrical'):
    print('Name:',name,'Roll no:',rollNo,'Branch:',branch)
```


```python
# Main program.
# Function call 1.
studentInfo(name = 'John')
# Function call 2.
studentInfo(name = 'Bob', rollNo = 10)
# Function call 3.
studentInfo(name = 'Jenny', rollNo = 5, branch = 'Computer Science')
```

    Name: John Roll no: 20 Branch: Electrical
    Name: Bob Roll no: 10 Branch: Electrical
    Name: Jenny Roll no: 5 Branch: Computer Science



```python
# Required Arguments in Python

# example error code
```


```python
# Program to find the area and perimeter of rectangle using function required arguments.
def rectangle(length, breadth):
    areaRec = length * breadth # Area of rectangle.
    perRec = 2 * (length + breadth) # Perimeter of rectangle.
    print("Area of rectangle = ",areaRec)
    print("Perimeter of rectangle = ",perRec)
```


```python
# Main program.
def main():
    ln = int(input("Enter the length of rectangle: "))
    br = int(input("Enter the breadth of rectangle: "))
    rectangle(ln) # Intentionaly missing one argument value.
```


```python
main() # function calling.
```

    Enter the length of rectangle:  20
    Enter the breadth of rectangle:  20



    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[16], line 1
    ----> 1 main() # function calling.


    Cell In[15], line 5, in main()
          3 ln = int(input("Enter the length of rectangle: "))
          4 br = int(input("Enter the breadth of rectangle: "))
    ----> 5 rectangle(ln)


    TypeError: rectangle() missing 1 required positional argument: 'breadth'



```python
# Keyword Arguments in Python
```


```python
# Displaying persons info.
def display(name, age, gender):
    print('Name:',name)
    print('Age:',age)
    print('Gender:',gender)
```


```python
def main():
 # First function call.
    display('John', 20, 'M') # function calling from another function.
 # Second function call.
    display('Jenny', 18, 'F')
```


```python
main() # function calling.
```

    Name: John
    Age: 20
    Gender: M
    Name: Jenny
    Age: 18
    Gender: F



```python
# Displaying persons info.
def display(name, age, gender):
    print('Name:',name)
    print('Age:',age)
    print('Gender:',gender)
def main():
  # First function call.
    display('Herry', age = 20, gender = 'M') # function calling from another function.
  # Second function call.
    display(age = 18, gender = 'F', name = 'Jimmy')
main() # function calling.
```

    Name: Herry
    Age: 20
    Gender: M
    Name: Jimmy
    Age: 18
    Gender: F



```python
# Variable length Arguments
```


```python
def my_function(*args): # args is the name of variable length parameters.
    "function docstring"
    # body of the function
    return [expression]

```


```python
# Example 1:
```


```python
# Function definition with variable length parameters. 
def my_function(*args): # Here, args is name of formal parameter.
    print(args)
print('Calling function with two arguments')
my_function(10, 20)

print('Calling function with three arguments')
my_function(10, 20, 30)
print('Calling function with four arguments')
my_function(20, 30, 40, 50)

```

    Calling function with two arguments
    (10, 20)
    Calling function with three arguments
    (10, 20, 30)
    Calling function with four arguments
    (20, 30, 40, 50)



```python
# Function definition with one formal parameter and variable length parameters.
def listDay(arg1, *arg2):
    print(arg1, arg2, sep="")
def main():
    listDay('Name of days are:', 'Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday')
main() # function calling.

```

    Name of days are:('Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday')



```python

```


```python

```


---
**Score: 20**