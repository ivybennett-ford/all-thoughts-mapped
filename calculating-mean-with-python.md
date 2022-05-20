---
tags:
  - python
  - astronomy
  - astrophysics
  - programming
---

The following code block returns the mean value of a set of [[flux|fluxes]]. It relies on the `statistics` module in python, a library of calculations which return descriptive statistics.

```python
from statistics import mean
fluxes = [23.3, 42.1, 2.0, -3.2, 55.6]
m = mean(fluxes)
print(m)
```
The mean can also be calculated manually, as we do when we [[calculate-1d-mean-stack]], or in the following way:

```python
fluxes = [23.3, 42.1, 2.0, -3.2, 55.6]
m = sum(fluxes) / len(fluxes)
# or count(fluxes) if you are continuously updating the list
print(m)
```

