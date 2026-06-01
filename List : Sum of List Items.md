# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program:

# Program to find the sum of all elements in a list

# Step 1: Take input from the user
n = int(input("Enter number of elements in the list: "))
arr = []

# Step 2: Read elements into the list
for i in range(n):
    num = int(input(f"Enter element {i+1}: "))
    arr.append(num)

# Step 3: Calculate sum
total = 0
for i in arr:
    total += i

# Step 4: Display result
print("Sum of all elements in the list is:", total)

<img width="1558" height="751" alt="image" src="https://github.com/user-attachments/assets/d0db64d3-ae04-4f53-987a-9c711e00e93c" />


## Output:
<img width="1558" height="751" alt="image" src="https://github.com/user-attachments/assets/058a16e5-41d7-4868-8df4-7a120c8acdd3" />


## Result:

The program successfully calculates and displays the sum of all elements in the list entered by the user.

