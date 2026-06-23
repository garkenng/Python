## Multiples of 3 and 5
### Summary<br>
Write a program that finds the sum of all natural numbers below 1000 (< 1000) that are multiples of 3 or 5, and prints it.
<br><br>
If we list all the natural numbers below 20 (<20) that are multiples of 3 or 5, we get 3, 5, 6, 9, 10, 12, 15, 18. The sum of these multiples is 78.
<br><br>
Note that 15 is only counted once.
<br><br>

```
def multiples_of_3_and_5(limit):
    total_sum = 0
    # Iterates up to (but excluding) the target limit
    for i in range(limit):
        if i % 3 == 0 or i % 5 == 0:
            total_sum += i
    return total_sum

result = multiples_of_3_and_5(1000)
print(result)
```
<br>

Output<br><br>

```
233168
```
