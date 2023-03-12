## Playing with Pandas

# Create a fake data frame
```python
import pandas as pd
import numpy as np


n_sample = 1000
n_outlier = 10
arr = np.random.randn(n_sample, 3)
outlier_arr = np.random.randn(n_outlier, 3) + [7, 9, 11]
columns = ['x1', 'x2', 'x3']
data = pd.DataFrame(arr, columns=columns)
outliers = pd.DataFrame(outlier_arr, columns=columns)
data = pd.concat([data, outliers])
data = data.sample(frac=1, random_state=42).reset_index(drop=True)
print(data.head())
```
