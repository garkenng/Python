## Sort students
## Summary<br>

Part 1
Write a function named sort_by_mark that take as argument a list of students and returns a copy of it sorted by mark in descending order.
<br><br>

```
my_class = [(25, "Shannon"), (50, "Alan"), (75, "Ada")]

def sort_by_mark(students):
    students.sort(key=lambda x: x[0], reverse=True)
    return students

print(sort_by_mark(my_class))
```
<br>

Part 2
Write a function named sort_by_name that take as argument a list of students and returns a copy of it sorted by name in ascending order.


```
my_class = [(25, "Shannon"), (50, "Alan"), (75, "Ada")]

def sort_by_name(students):
    students.sort(key=lambda x: x[1], reverse=False)
    return students

print(sort_by_name(my_class))
```
<br>








