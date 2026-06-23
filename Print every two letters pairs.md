## Print every two letters pairs
### Summary<br>

Provide a script printing every possible pairs of two letters, only lower case, one by line, ordered alphabetically.
<br><br>
So your output should look like:
<br><br>

```
$ python3 solution.py
aa
ab
...
ba
bb
...
zz
```
<br>

Solution.<br><br>

```
import string

alphabet = string.ascii_lowercase

for first_letter in alphabet:
    for second_letter in alphabet:
        print(first_letter + second_letter)
```
<br>
