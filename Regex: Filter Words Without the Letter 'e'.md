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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []
for i in items:
    if not re.search(r"e", i):  # Check if 'e' is present
        l1.append(i)

print("Words without the letter 'e':", l1)
```
## Output
<img width="716" height="673" alt="image" src="https://github.com/user-attachments/assets/c7efe8a4-de48-4316-aaee-4f99fc055a4d" />

## Result
Thus, the output is verifed successfully
