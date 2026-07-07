```python
import numpy
```


```python
data = numpy.loadtxt(fname="inflammation-01.csv", delimiter=",")
```


```python
import matplotlib.pyplot
image = matplotlib.pyplot.imshow(data)
matplotlib.pyplot.show()
```


![png](output_2_0.png)



```python
Ave_inflammation = numpy.mean(data, axis=0)
Ave_plot = matplotlib.pyplot.plot(Ave_inflammation)
matplotlib.pyplot.show()
```


![png](output_3_0.png)



```python
Max_plot = matplotlib.pyplot.plot(numpy.max(data, axis=0))
matplotlib.pyplot.show()
```


![png](output_4_0.png)



```python
Min_plot = matplotlib.pyplot.plot(numpy.min(data, axis=0))
matplotlib.pyplot.show()
```


![png](output_5_0.png)



```python
fig = matplotlib.pyplot.figure(figsize=(10.0, 3.0))

axs1 = fig.add_subplot(1, 3, 1)
axs2 = fig.add_subplot(1, 3, 2)
axs3 = fig.add_subplot(1, 3, 3)

axs1.set_ylabel("Average")
axs1.plot(numpy.mean(data, axis=0))

axs2.set_ylabel("Max")
axs2.plot(numpy.max(data, axis=0))

axs3.set_ylabel("Min")
axs3.plot(numpy.min(data, axis=0))

fig.tight_layout()

matplotlib.pyplot.savefig("inflammation.png")
matplotlib.pyplot.show()
```


![png](output_6_0.png)



```python

```
