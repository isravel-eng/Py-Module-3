## ISRAVEL Y (25018187)

# 1. List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```py
l=[1,2,3,4,5,6,7,8,9]
print(sum(l))
```

## Output
<img width="273" height="92" alt="Screenshot 2025-10-20 004453" src="https://github.com/user-attachments/assets/94011434-0793-4c5f-9903-80157c6869f2" />

## Result
Successfully wrote a Python program that calculates the **sum of all elements** in a list.

# 2. Regex in Python: Filter Words Without the Letter 'e'

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

## 🧾 Programv
```py
import re
l=[]
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r'e',i):
        l.append(i)
print(l)
```
## Output
<img width="513" height="202" alt="image" src="https://github.com/user-attachments/assets/fc157eea-673a-42e8-b75c-a8e8421e6a38" />

## Result
Successfully wrote a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.


# 4. Strings-Remove Nth Index Character from a String

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
```py
string=input()
n=int(input())
es=''
for i in range(len(string)):
    if i!=n:
        es+=string[i]
print(es)
```
## Output
<img width="311" height="238" alt="image" src="https://github.com/user-attachments/assets/32ff9263-fb76-49a8-953b-497d5a87bbea" />

## Result
Successfully wrote a Python program that accepts a string and removes the character at a specified index.

# 4. Strings-Palindrome Check in Python (Without Built-in Functions)

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
```py
string="google"
print("the string is a palindrome." if string==string[::-1] else " it is not a palindrome")
```
## Output
<img width="906" height="92" alt="image" src="https://github.com/user-attachments/assets/dc1905a7-0e51-4c55-b73a-976b34df7985" />

## Result
Successfully wrote a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

# 5. Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```PY
tuple_=eval(input())
print('n' in tuple_)
print('8' in tuple_)
```

## Output
<img width="393" height="122" alt="image" src="https://github.com/user-attachments/assets/381bfe9e-0ffe-4354-97c4-789ca141072d" />


## Result
Successfully wrote a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.
