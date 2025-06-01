# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```python
def palindrome(wrd):
    x1=wrd[::-1]
    if wrd == x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
        
string =input()
palindrome(string)
```
## Output

![image](https://github.com/user-attachments/assets/d60a7e94-fdb9-48cb-a98b-d74fba227a3c)

## Result

Thus the program executed successfully.
