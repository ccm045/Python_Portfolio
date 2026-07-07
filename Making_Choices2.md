```python
import numpy
```


```python
data = numpy.loadtxt(fname="inflammation-01.csv", delimiter=",")
```


```python
max_inflammation_0 = numpy.max(data, axis=0)[0]
```


```python
max_inflammation_20 = numpy.max(data, axis=0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print("suspicious looking maxima!")
```

    suspicious looking maxima!



```python
max_inflammation_20 = numpy.max(data, axis=0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print("suspicious looking maxima!")
    
elif numpy.sum(numpy.min(data, axis=0)) == 0:
    print("Minima add up to zero")
    
else:
    print("Seems ok")
```

    suspicious looking maxima!



```python
data = numpy.loadtxt(fname="inflammation-03.csv", delimiter=",")

max_inflammation_0 = numpy.max(data, axis=0)[0]

max_inflammation_20 = numpy.max(data, axis=0)[20]

if max_inflammation_0 == 0 and max_inflammation_20 == 20:
    print("suspicious looking maxima")
elif numpy.sum(numpy.min(data, axis=0)) == 0:
    print("Minima add up to zero! — HEALTHY PARTICIPANT ALERT")
else:
    print("Seems ok")
```

    Minima add up to zero! — HEALTHY PARTICIPANT ALERT

