# List Operations in Python: Sum of List Items
## 🎯 Aim
To write a Python program that calculates the sum of all elements in a list.

## 🧠 Algorithm
Define a list of numbers. Use Python’s built-in sum() function to calculate the total. Print the result.

## 🧾 Program
```
numbers = [10, 20, 30, 40, 50] 
total = sum(numbers)
print("Sum of the list items is:", total)
```
## Output
Screenshot 2025-10-20 163747
Result
Thus To write a Python program that calculates the sum of all elements in a list has been executed sucessfully.

# Regex in Python: Filter Words Without the Letter 'e'
## 🎯 Aim
To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## 🧠 Algorithm
Import the re module. Initialize an empty list l1 to store results. Define a list of words: items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner'] Iterate through each word in the list: Use re.search(r"e", i) to check if the word contains 'e'. If not, append the word to l1. Print the final filtered list.

## 🧾 Program
```
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

for i in items:
    if not re.search(r'e', i):
        l1.append(i)

print("Filtered words without 'e':", l1)
```
## Output
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/db2d8e77-1c58-420c-995c-5d982c54c7be" />

## Result
Thus To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) has been executed sucessfully.

# 🧹 Strings-Remove Nth Index Character from a String
## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
Define a function named remove that takes the input string as an argument. Read the index n from the user input. Initialize an empty string a to store the new string. Iterate over each index of the string using a for loop. Check if the current index i is not equal to n. If i != n, append the character at index i to string a. After the loop, return the modified string a. Print the final result.

## 💻 Program
```
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

input_string = input("Enter a string: ")
result = remove(input_string)
print("String after removal:", result)
```
## Output
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/f68e1f3e-1cda-45d5-9219-a32410807d45" />

## Result
Thus To write a Python program that accepts a string and removes the character at a specified index has been executed sucessfully

# Strings-Palindrome Check in Python (Without Built-in Functions)
## 🎯 Aim
To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
Assign the string "google" to a variable. Reverse the string manually using slicing ([::-1]). Compare the original string with the reversed string. If they are equal, print that the string is a palindrome. Otherwise, print that it is not a palindrome. Execute the program.

## 🧾 Program
```
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print(f'"{string}" is a palindrome.')
else:
    print(f'"{string}" is not a palindrome.')
```
## Output
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/fb598989-ef0a-482f-9f0a-c0753d75d16f" />

## Result
Thus To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed sucessfully.

# Tuple in Python: Check Element Existence
## 🎯 Aim
To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## 🧠 Algorithm
Define a tuple x with some letters and numbers. Use the in operator to check if the string 'n' exists within the tuple. Use the in operator to check if the integer 8 exists within the tuple. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 4, 8, 9)

# Check if 'n' exists
exists_n = 'n' in x
# Check if 8 exists
exists_8 = 8 in x

print(f"'n' exists in tuple: {exists_n}")
print(f"8 exists in tuple: {exists_8}")
```
## Output
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/16eaf967-8be3-4b25-8cab-8413f97493ae" />

## Result
Thus To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple has been executed sucessfully.
