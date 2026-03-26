# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
my_dict = {'Ten': 10, 'Twenty': 20, 'Thirty': 30, 'Five': 5}
sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Original Dictionary:", my_dict)
print("Dictionary Sorted by Keys:", sorted_by_keys)
print("Dictionary Sorted by Values:", sorted_by_values)

## Sample Output
<img width="818" height="278" alt="image" src="https://github.com/user-attachments/assets/b01e9928-7679-4629-8662-7d053af8b9ce" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
