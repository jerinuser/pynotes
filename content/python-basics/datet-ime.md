---
title: Datet-Ime
date: 2025-01-12
author: Your Name
cell_count: 3
score: 0
---

```python
from datetime import datetime

def string_to_date(date_string):
    date_object = datetime.strptime(date_string, "%Y-%m-%d")
    return date_object

# Example usage
date_string = "2025-01-02"
result = string_to_date(date_string)
print(result)
```

    2025-01-02 00:00:00



```python
def check_leap_year(year):
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        return "Leap year"
    else:
        return "Not a leap year"


year = 2024
result = check_leap_year(year)
print(result)

```

    Leap year



```python

```


---
**Score: 0**