---
title: Pandas-Df
date: 2025-01-13
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
import pandas as pd

```


```python
data = {'name': ['Jason', 'Molly', 'Tina', 'Jake', 'Amy'], 
        'year': [2012, 2012, 2013, 2014, 2014], 
        'reports': [4, 24, 31, 2, 3],
        'coverage': [25, 94, 57, 62, 70]}
```


```python
df = pd.DataFrame(data, index = ['Cochice', 'Pima', 'Santa Cruz', 'Maricopa', 'Yuma'])
```


```python
capitalizer = lambda x: x.upper()
```


```python
above_20 = lambda x: 1 if(x > 20) else 0
```


```python
df['name'] = df['name'].apply(capitalizer)
```


```python
print(df.describe())
```

             year    reports   coverage
    count     5.0   5.000000   5.000000
    mean   2013.0  12.800000  61.600000
    std       1.0  13.663821  24.905823
    min    2012.0   2.000000  25.000000
    25%    2012.0   3.000000  57.000000
    50%    2013.0   4.000000  62.000000
    75%    2014.0  24.000000  70.000000
    max    2014.0  31.000000  94.000000



```python

```


---
**Score: 10**