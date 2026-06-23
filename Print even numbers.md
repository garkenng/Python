## Print even numbers
### Summary<br>
Write a function printing every even numbers in the given range, one number per line.<br><br>

```
def print_even_numbers(start, stop):
    for i in range(start, stop):
        if i % 2 == 0:
            print(i)

print_even_numbers(0, 10)
```
<br>

Output<br><br>

```
0
2
4
6
8
```
