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

## 🧾 Program:
# Program to check palindrome without built-in functions

s = "google"

# Step 1: Find reverse manually
rev = ""
for ch in s:
    rev = ch + rev   # building reverse string

# Step 2: Compare original and reversed string
if s == rev:
    print(s, "is a palindrome")
else:
    print(s, "is not a palindrome")

<img width="1501" height="708" alt="image" src="https://github.com/user-attachments/assets/ff235fcf-4e45-4dee-b64e-fec1dfd1f184" />


## Output:

<img width="1501" height="708" alt="image" src="https://github.com/user-attachments/assets/b988bebc-eb30-4055-9206-dea36430280b" />


## Result:
The program checks whether the string "google" is a palindrome or not by reversing it manually and comparing it with the original string.


