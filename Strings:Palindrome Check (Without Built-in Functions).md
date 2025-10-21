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
a = input() 
rev = a[::-1] 
if a == rev: 
   print("The entered string is palindrome") 
else: 
   print("The entered string is not palindrome")

## Output
<img width="917" height="202" alt="image" src="https://github.com/user-attachments/assets/b13f88c6-ef3c-45cf-b0eb-ab847bf243db" />

## Result
Thus the program to check whether the string is a palindrome or not, without using built-in palindrome checking functions is executed successfully.
