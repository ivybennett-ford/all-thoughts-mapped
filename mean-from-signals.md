---
tags:
  - code
  - astrophysics
  - computational-methods
  - data
---
```python
# Write your mean_datasets function here
	import numpy as np
	def mean_datasets(files):
	  n = len(files)
	  if n > 0:
		data = np.loadtxt(files[0], delimiter=',')
		for i in range(1,n):
		  data += np.loadtxt(files[i], delimiter=',')
	  data_mean = data / n
	  return np.round(data_mean, 1)
	if __name__ == '__main__':
				  # Run your function with the first example from the question:
				  print(mean_datasets(['data1.csv', 'data2.csv', 'data3.csv']))
				  print(mean_datasets(['data4.csv', 'data5.csv', 'data6.csv']))
```

You can use this to test your function.
Any code inside this `if` statement will be ignored by the automarker.