## Fix is_anagram
### Summary<br>
This function takes two parameters:
<br><br>
left: it expects just one word, as a Python str.
<br>
right: it also expects just one word, as a Python str.
<br><br>
the function should return True if the two words are anagrams, False otherwise. Sadly there's a small error in my implementation (try to submit it if you don't catch it), can you fix it? <br><br>

Original code.<br><br>

```
def is_anagram(left, right):
    left_letters = sorted(left)
    right_letters = sorted(right)
    return left_letters = right_letters
```
<br>

Solution.<br><br>

```
def is_anagram(left, right):
    left_letters = sorted(left)
    right_letters = sorted(right)
    return left_letters == right_letters
```

