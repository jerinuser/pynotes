---
title: Correlation-1
date: 2025-01-13
author: Your Name
cell_count: 7
score: 5
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
# necessary modules
import pandas as pd
import numpy as np
```


```python
def histogram_intersection(a, b):
    v = np.minimum(a, b).sum().round(decimals=1)
    return v
```


```python
def startpy():

    df = pd.DataFrame([(.2, .3), (.0, .6), (.6, .0), (.2, .1)],
                  columns=['dogs', 'cats'])

    cor_result = df.corr(method=histogram_intersection)

    return cor_result
```


```python
startpy()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>dogs</th>
      <th>cats</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>dogs</th>
      <td>1.0</td>
      <td>0.3</td>
    </tr>
    <tr>
      <th>cats</th>
      <td>0.3</td>
      <td>1.0</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


---
**Score: 5**