---
title: Email-Check
date: 2025-01-25
author: Your Name
cell_count: 5
score: 5
---

```python
# program to check a valid email 
```


```python
import re
```


```python
def email_check():
    email = input("Enter your email: ")

    if not email.endswith(".com"):
        print("Invalid: Email must end with '.com'")
        return

    if "@" not in email:
        print("Invalid: Email must contain '@'")
        return

    if email[0].isdigit():
        print("Invalid: Email should not start with a digit")
        return

    print("Valid")

# Example usage
email_check()

```

    Enter your email:  jrrin@.com


    Valid



```python
email_check()
```

    Enter your email:  jerin29@gmail.com


    Valid



```python

```


---
**Score: 5**