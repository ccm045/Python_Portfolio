```python
fahrenheit_val = 99
celsius_val = ((fahrenheit_val - 32) * (5/9))

print(celsius_val)
```

    37.22222222222222



```python
fahrenheit_val2 = 43
celsius_val2 = (fahrenheit_val2 - 32) * 5/9

print(celsius_val2)
```

    6.111111111111111



```python
def explicit_fahr_to_celsius(temp):
    converted = ((temp - 32) * (5/9))
    return converted
```


```python
def fahr_to_celsius(temp):
    return ((temp - 32) * (5/9))
```


```python
fahr_to_celsius(32)
```




    0.0




```python
explicit_fahr_to_celsius(32)
```




    0.0




```python
print("freezing point of water:", fahr_to_celsius(32), "C")

print("boiling point of water:", fahr_to_celsius(212), "C")
```

    freezing point of water: 0.0 C
    boiling point of water: 100.0 C



```python
def celsius_to_kelvin(temp_c):
    return temp_c + 273.15

print("freezing point of water in kelvin", celsius_to_kelvin(0))
```

    freezing point of water in kelvin 273.15



```python
def fahr_to_kelvin(temp_f):
    temp_c = fahr_to_celsius(temp_f)
    temp_k = celsius_to_kelvin(temp_c)
    return temp_k

print("boiling point of water in kelvin", fahr_to_kelvin(212))
```

    boiling point of water in kelvin 373.15



```python
print("Again, temperature in kelvin was", temp_k)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-15-15dfb04dc3ef> in <module>
    ----> 1 print("Again, temperature in kelvin was", temp_k)
    

    NameError: name 'temp_k' is not defined



```python
temp_kelvin = fahr_to_kelvin(212.0)
print("temperature in Kelvin was", temp_kelvin)
```

    temperature in Kelvin was 373.15



```python
temp_kelvin
```




    373.15




```python
def print_temperatures():
    print("temperature in Fahrenheit was:", temp_fahr)
    print("temperature in Kelvin was:", temp_kelvin)

temp_fahr = 212.0
temp_kelvin = fahr_to_kelvin(temp_fahr)

print_temperatures()
```

    temperature in Fahrenheit was: 212.0
    temperature in Kelvin was: 373.15



```python

```
