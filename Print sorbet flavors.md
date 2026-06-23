## Print sorbet flavors
### Summary<br>
You're working for a restaurant and they're asking you to generate the sorbet menu.
<br><br>
Provide a script printing every possible sorbet duos from a given list of flavors.
<br><br>
Don't print recipes with twice the same flavor (no "Chocolate, Chocolate"), and don't print twice the same recipe (if you print "Vanilla, Chocolate", don't print "Chocolate, Vanilla", or vice-versa).
<br><br>
The flavors are:
<br><br>

```
FLAVORS = [
    "Banana",
    "Chocolate",
    "Lemon",
    "Pistachio",
    "Raspberry",
    "Strawberry",
    "Vanilla",
]
```
<br>

Print one duo per line, and separate flavors by comas, so your output should look like:
<br><br>

```
Banana, Chocolate
Banana, Lemon
Banana, Pistachio
Banana, Raspberry
Banana, Strawberry
Banana, Vanilla
Chocolate, Lemon
```
<br>

Solution.<br><br>

```
FLAVORS = [
    "Banana",
    "Chocolate",
    "Lemon",
    "Pistachio",
    "Raspberry",
    "Strawberry",
    "Vanilla",
]

for i, first_flavor in enumerate(FLAVORS):
    for second_flavor in FLAVORS[i + 1:]:
        print(f"{first_flavor}, {second_flavor}")
```
<br>

Output.<br><br>

```
Banana, Chocolate
Banana, Lemon
Banana, Pistachio
Banana, Raspberry
Banana, Strawberry
Banana, Vanilla
Chocolate, Lemon
Chocolate, Pistachio
Chocolate, Raspberry
Chocolate, Strawberry
Chocolate, Vanilla
Lemon, Pistachio
Lemon, Raspberry
Lemon, Strawberry
Lemon, Vanilla
Pistachio, Raspberry
Pistachio, Strawberry
Pistachio, Vanilla
Raspberry, Strawberry
Raspberry, Vanilla
Strawberry, Vanilla
```

