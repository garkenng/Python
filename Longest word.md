## Longest word
### Summary<br>
Write a function giving the longest word in a given text.
<br><br>
Your function should be named longest_word, take a single argument text and return a string which should be the longest word in the given text.
<br><br>

```
def longest_word(text):
    words = text.split()
    longest_word = max(words, key=len)
    return longest_word
```
<br>
