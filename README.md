

# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = [5, 10, 15, 20, 25]
total = sum(numbers)
print("Sum of list items:", total)
```

## Output

<img width="248" height="72" alt="image" src="https://github.com/user-attachments/assets/088d9a75-2ed6-4e38-ba7e-c8eabe47620e" />


## Result

Thus, the Python program successfully calculates the sum of all elements in a list.


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

## 🧾 Program
```

import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Filtered words:", l1)
```
## Output

<img width="418" height="76" alt="image" src="https://github.com/user-attachments/assets/6118bdd9-0189-4115-8ae2-b6866ce15ddc" />


## Result

Thus, the Python program successfully filters and prints the words that do not contain the letter 'e' using regular expressions.


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

## 💻 Program
```
def remove(s):
    n = int(input("Enter index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a

string = input("Enter a string: ")
result = remove(string)
print("Modified string:", result)
```

## Output

<img width="292" height="123" alt="image" src="https://github.com/user-attachments/assets/b8f82e47-4841-41af-bab1-e28d9b8dfbba" />


## Result

Thus, the Python program successfully removes the Nth index character from the given string.


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
    print("Not Palindrome")
```

## Output

<img width="243" height="90" alt="image" src="https://github.com/user-attachments/assets/b5418f5b-ec20-4a9b-b54b-61876a5deb08" />


## Result
Thus, the Python program successfully checks whether the string "google" is a palindrome without using built-in functions.


# Tuple in Python: Check Element Existence


## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuplex = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print("8" in tuplex)
```
## Output

![image](https://github.com/user-attachments/assets/5c6097a5-3f2c-49eb-bea4-4a5d83819a80)

## Result
Thus,the program has been execueted successfully.
