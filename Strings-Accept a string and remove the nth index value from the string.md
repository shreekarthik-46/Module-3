
#  3)c)Strings-Remove Nth Index Character from a String

##  Aim
To write a python function that accepts a string and removes the 3rd index value from the string

##  Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Using string slicing. slice the index of a string forward and backward as per the index and combine to form a new string using`+`.
4. Store the new string in result and print it.

##  Program
```
def remove(input_string):
    result=input_string[:3]+input_string[4:]
print(result)
```

## Output
![str-rem](https://github.com/user-attachments/assets/9350fc43-c1bd-4a2d-9f66-9fff970ccc6f)


## Result
Thus a python function that accepts a string and removes the 3rd index value from the string is created
