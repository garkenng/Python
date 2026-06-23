## Sum of even numbers <= 100
### Summary<br>
Provide a script that prints the sum of every even numbers in the range [0; 100].<br><br>

```
def print_total_even_numbers(start, stop):
    sum = 0
    for i in range(start, stop):
        if i % 2 == 0:
            sum = sum + i
    return(sum)
    
print(print_total_even_numbers(0,101))
```
<br>

Output<br><br>

```
2550
```
