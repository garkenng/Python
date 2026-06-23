## Comparisons
### Summary<br>
Find the biggest value in a given list.<br><br>

```
the_list = [
    143266561,
    1738152473,
    312377936,
    1027708881,
    1871655963,
    1495785517,
    1858250798,
    1693786723,
    374455497,
    430158267,
]
```
<br>

Solution<br><br>

```
the_list = [
    143266561,
    1738152473,
    312377936,
    1027708881,
    1871655963,
    1495785517,
    1858250798,
    1693786723,
    374455497,
    430158267,
]

biggest_value = 0 

for num in the_list:
    if num > biggest_value:
        biggest_value = num

print(biggest_value)
```
<br>

Output<br><br>

```
1871655963
```


