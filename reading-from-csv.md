---
tags:
  - code
  - data
  - python
  - astrophysics
  - computational-methods
---
These are examples for reading numbers from a CSV, with numpy and without:

```python
data = []
	for line in open('data.csv'):
	  data.append(line.strip().split(','))

	print(data)
```

Now we can store the data in lists, we need to convert each item from a string to a float. We could do this using nested `for` loops:

```python
data = []
	
	for line in open('data.csv'):
	 row = []
	 for col in line.strip().split(','):
	 row.append(float(col))
	 data.append(row)
	
	print(data)
```

NumPy has a simpler `asarray` function to do this conversion:

import numpy as np

```python
data = []
	
	for line in open('data.csv'):
	 data.append(line.strip().split(','))

	data = np.asarray(data, float)

	print(data)
```

Most NumPy functions operate on the whole array at once rather than individual items.

Words and notes taken from [[data-driven-astronomy]] programming notes

