# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program:

# Given tuple
t = ('a', 'b', 'n', 3, 8, 10)

# Elements to check
elem1 = 'n'
elem2 = 8

# Check existence
if elem1 in t:
    print(f"'{elem1}' exists in the tuple")
else:
    print(f"'{elem1}' does not exist in the tuple")

if elem2 in t:
    print(f"{elem2} exists in the tuple")
else:
    print(f"{elem2} does not exist in the tuple")

<img width="1541" height="714" alt="image" src="https://github.com/user-attachments/assets/8c125f36-198f-44b6-91ed-1a34366a3b68" />

## Output:

<img width="1541" height="714" alt="image" src="https://github.com/user-attachments/assets/da4f4562-96db-4996-a75c-a9f56074b0ff" />


## Result:

The program successfully checks the presence of the elements 'n' and 8 in the given tuple and confirms that both elements exist in the tuple.
