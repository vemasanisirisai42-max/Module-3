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
print("The sum of list elements is:", total)
```

## Output
<img width="957" height="763" alt="image" src="https://github.com/user-attachments/assets/53aefb7e-532f-49d3-bf16-1df1365e2f12" />

## Result
Thus, the output is verified successfully
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
def remove(string, n):
    return string[:n] + string[n+1:]  # Concatenating parts before and after n

string = input("Enter a string: ")
n = int(input("Enter index to remove: "))

if 0 <= n < len(string):
    result = remove(string, n)
    print("Modified string:", result)
else:
    print("Invalid index! Please enter a valid index.")
```

## Output
<img width="716" height="734" alt="image" src="https://github.com/user-attachments/assets/140fcd9d-6c67-4ee5-86e8-2b45af9ab872" />

## Result
Thus, the output is verified successfully
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
# Assign the string to a variable
string = "google"

# Reverse the string manually using slicing
reversed_string = string[::-1]

# Check if the original string matches the reversed string
if string == reversed_string:
    print(f'"{string}" is a palindrome!')
else:
    print(f'"{string}" is not a palindrome.')
```

## Output
<img width="832" height="744" alt="image" src="https://github.com/user-attachments/assets/ef202637-49dc-41bf-b57e-8e391324af3c" />

## Result
Thus, the output is verified successfully
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
# Define a tuple with letters and numbers
x = ('a', 'b', 'c', 'n', 5, 8, 12)

# Check if 'n' is in the tuple
if 'n' in x:
    print("'n' is present in the tuple.")
else:
    print("'n' is not present in the tuple.")

# Check if 8 is in the tuple
if 8 in x:
    print("8 is present in the tuple.")
else:
    print("8 is not present in the tuple.")
```

## Output
<img width="949" height="710" alt="image" src="https://github.com/user-attachments/assets/08ec492c-c86c-464b-a329-59a35266acbe" />

## Result
Thus, the output is verified successfully
