## Temperatures
### Summary<br>

Write functions to convert from Fahrenheit to Celsius and vice-versa.
<br><br>
Your functions should look like:
<br><br>

```
def fahrenheit_to_celsius(temp):
    ...

def celsius_to_fahrenheit(temp):
    ...
```
<br>

Solution.<br><br>

```
def fahrenheit_to_celsius(temp):
    return (temp - 32) * 5/9

def celsius_to_fahrenheit(temp):
    return (temp * 9/5) + 32
```
<br>
