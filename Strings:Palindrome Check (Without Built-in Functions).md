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
```
s = "google"
rev = s[::-1]
if s == rev:
    print("Palindrome")
else:
    print("Not a palindrome")
```
## Output
<img width="308" height="123" alt="{A6AB92F4-961F-489E-AE9D-1A400D4E8221}" src="https://github.com/user-attachments/assets/ecf3e04f-3d0f-4828-a16a-3af134d0706c" />
