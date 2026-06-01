# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program:
# Program to remove a character at a specified index

# Step 1: Input string
s = input("Enter a string: ")

# Step 2: Input index
index = int(input("Enter index to remove: "))

# Step 3: Validate index and remove character
if index < 0 or index >= len(s):
    print("Invalid index")
else:
    result = s[:index] + s[index+1:]
    print("Resulting string:", result)

<img width="1444" height="697" alt="image" src="https://github.com/user-attachments/assets/13e87df5-b8ad-4848-b619-5eb2d60e4b1b" />


## Output:

<img width="1444" height="697" alt="image" src="https://github.com/user-attachments/assets/80363cce-f475-4215-9626-e99e2c1daa8a" />


## Result:

The program successfully removes the character at the specified index from the given string and displays the updated string.
