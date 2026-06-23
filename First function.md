## First function
### Summary<br>
Write a function computing the perimeter of a circle given its radius.
<br><br>
Your function should be named circle_perimeter(radius), where the radius parameter is the radius of a cirle.
<br><br>
Your function should return the perimeter of a circle of the given radius.
<br><br>
To test it, we will import your function and try it with different values, such as:

```
>>> circle_perimeter(1)
6.283185307179586
>>> circle_perimeter(10)
62.83185307179586
>>> circle_perimeter(100)
628.3185307179587
```
<br>

Solution.<br><br>

```
import math

def circle_perimeter(r):
    perimeter = 2 * math.pi * r
    return perimeter


print(circle_perimeter(1))
print(circle_perimeter(10))
print(circle_perimeter(100))
```
<br>
