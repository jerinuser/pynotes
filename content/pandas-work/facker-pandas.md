---
title: Facker-Pandas
date: 2025-03-21
author: Your Name
cell_count: 10
score: 10
---

```python
import pyutil as pyu
pyu.get_local_pyinfo()
```




    'conda env: py311; pyv: 3.11.9 (main, Apr 19 2024, 16:48:06) [GCC 11.2.0]'




```python
print(pyu.ps2("pandas"))
```

    pandas==2.2.3
    



```python
from enum import Enum
from faker import Faker
import random
import pandas as pd
```


```python
fake = Faker()
```


```python
class JobRole(Enum):
    ENGINEER = "Engineer"
    MANAGER = "Manager"
    ANALYST = "Analyst"
    CONSULTANT = "Consultant"
    DEVELOPER = "Developer"
```


```python
def generate_data(num_records):
    data = []
    for _ in range(num_records):
        record = {
            "name": fake.name(),
            "email": fake.email(),
            "address": fake.address(),
            "job_role": random.choice(list(JobRole)).value,
            "company": fake.company(),
            "phone_number": fake.phone_number()
        }
        data.append(record)
    return data
```


```python
def generate_batch():
    batch = []
    for _ in range(5):
        record = {
            "name": fake.name(),
            "email": fake.email(),
            "address": fake.address(),
            "job_role": random.choice(list(JobRole)).value,
            "company": fake.company(),
            "phone_number": fake.phone_number()
        }
        batch.append(record)
    return batch
```


```python

def startpy():

    # Initialize an empty CSV file and write headers first
    csv_file_path_incremental = 'user1.csv'
    df = pd.DataFrame(generate_batch())  # Generate initial 5 rows for headers
    df.to_csv(csv_file_path_incremental, index=False, mode='w')  # Write headers with initial data

    # Generate remaining 995 rows in increments of 5 and append to CSV
    for _ in range(199):  # Remaining 199 batches of 5 rows each = 995 rows
        batch_data = generate_batch()
        batch_df = pd.DataFrame(batch_data)
        batch_df.to_csv(csv_file_path_incremental, index=False, mode='a', header=False) 
```


```python
startpy()
```


```python

```


---
**Score: 10**