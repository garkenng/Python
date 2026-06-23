## Distance
### Summary<br>

Find the distance between the two furthest apart values in a list.
<br><br>
Create a dist function, receiving a list of numbers (integers or floating points), and returning the bigger distance between any two given values, so typically the distance between the biggest and the smallest, like:
<br><br>

```
>>> dist([1, 2, 3])
2
>>> dist([1, 2, 3, 2.5])
2
>>> dist([1, 2, 3, 2.5, 3.5])
2.5
>>> dist([1, 2, 3, 2.5, 3.5, 120])
119
>>> dist([1, 2, 3, 2.5, 3.5, 120, -1000])
1120
```
<br>

Solution.<br><br>

```
def dist(points):
    max_value = max(points)
    min_value = min(points)
    difference = max_value - min_value
    return difference
```
