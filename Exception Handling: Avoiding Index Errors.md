# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
list1 = [10, 20, 30, 40]
try:
    print("Element:", list1[5])  # Index out of range
except IndexError:
    print("You're out of list range")

## Output
<img width="449" height="182" alt="image" src="https://github.com/user-attachments/assets/9a5efab3-7c0a-4a9d-b278-39f69faefe2b" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
