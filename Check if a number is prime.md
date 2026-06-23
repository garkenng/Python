## Check if a number is prime
### Summary<br>

Define the function is_prime(n).
<br><br>
n is number that the function is_prime takes as a parameter.
<br><br>
The function is_prime return True if n is a prime number, False otherwise.
<br><br>

Solution.<br><br>

```
import math

def is_prime(n):
    if n <= 1:
        return False
        
    for i in range(2, int(math.sqrt(n)) + 1):
        if n % i == 0:
            return False  
            
    return True 
```
<br>
