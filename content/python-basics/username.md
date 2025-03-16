---
title: Username
date: 2025-03-16
author: Your Name
cell_count: 3
score: 0
---

```python
import re

```


```python
def valid_username(username):
    if username[0].isdigit():
        return False
    if len(username) > 15:
        return False
    return True

usernames_input = input("Enter usernames separated by commas: ")

usernames = usernames_input.split(',')

for username in usernames:
    username = username.strip()  
    print(f"Username: {username} -> Valid")

```

    Enter usernames separated by commas:  jerin,dass


    Username: jerin -> Valid
    Username: dass -> Valid



```python

```


---
**Score: 0**