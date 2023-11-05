---
tags:
  - 🌱
  - ComputerScience
date: 18--Sep--2023
---

# Parallel identification

The below can be parallelised. There is no shared data dependency among each loop.
```python
# example 1
a = list()
for i in range(n):
    a[i] = a[i] + 1
# example 2
for i in range(4):
    a[i] + a[i+5]
# example 3
for i in range(n):
    a[2*i] = b[i] + c[i] # even elements of a
    d[i] = a[1*i-1] # odd elements of a
```

The following code cannot be parallelised because there is data dependency.
```python
for i in range(n)
    a[i]=a[i] + a[i-1]
```



---
Links: 