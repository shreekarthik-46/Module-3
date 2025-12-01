# 3)b) Regex in Python: Filter Words Without the Letter 'e'

##  Aim
To write a Python program that find sequences of Upper case letters joined with a '@'.
##  Algorithm
1. Import the `re` module.
2. IGet the user input and store it in a variable a.
3. Define the condition as `[A-Z]+@+[A-Z]` store it in the variable called reg.
4. Write a regex function for matching the condition
5. Print wheather the match is found using if-else statement.
##  Program
```
import re
a=input()
reg='[A-Z]+@+[A-Z]'
match=re.match(reg,a)
if match:
    print("Found a match!")
else:
    print("Not matched!")
```
## Output

![regex](https://github.com/user-attachments/assets/0db60f5f-5483-4e98-90a3-3f8df02806c6)

## Result
Thus a Python program that find sequences of Upper case letters joined with a '@' is created.
