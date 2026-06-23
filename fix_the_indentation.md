## Fix the indentation
### In the given snippet, there's a bug: there's no indentation. Your goal is to fix it (by just adding 4 spaces at the right place).
<br><br>
The code should display:
<br><br>

```
Gonna knock three times:
*knock*
*knock*
*knock*
- Who's there?
```
<br>



print("Gonna knock three times:")
for i in range(3):
    print("*knock*")
print("- Who's there?")
