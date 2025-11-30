# 3)d) Strings-Palindrome Check in Python (Without Built-in Functions)

##  Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program
```
def palindrome(a):
    mid = (len(a)-1)//2    
    start = 0                
    last = len(a)-1
    flag = 0
    while(start <= mid):
        if (a[start]== a[last]):
            start+=1
            last-=1
        else:
            flag = 1
            break;
             
    if flag==0:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
        
        
string =input()
palindrome(string)
```
## Output

![pal-str](https://github.com/user-attachments/assets/e7887841-d23b-47ff-a301-531512c512c5)

## Result
Thus a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is created.


