# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program:
import re

# Step 1: Take input list from user
n = int(input("Enter number of elements: "))
lst = []

for i in range(n):
    item = input(f"Enter element {i+1}: ")
    lst.append(item)

# Step 2: Filter elements that do NOT contain 'e' or 'E'
filtered_list = []

for item in lst:
    if not re.search(r"e", item, re.IGNORECASE):
        filtered_list.append(item)

# Step 3: Display result
print("Elements without letter 'e':", filtered_list)

<img width="1621" height="739" alt="image" src="https://github.com/user-attachments/assets/f46aa62a-cce8-4543-adf9-3c70390722e3" />

## Output:

<img width="1621" height="739" alt="image" src="https://github.com/user-attachments/assets/6bb4bddc-3d32-47d2-b12e-a3aa8d1d4017" />


## Result:

The program successfully filters the list and returns only those elements that do not contain the letter 'e' (case-insensitive) using regular expressions.
