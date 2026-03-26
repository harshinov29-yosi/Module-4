## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Forty': 40, 'Fifty': 50}
result = merge(dict1, dict2)
print("Merged Dictionary:", result)

## Output
<img width="814" height="189" alt="image" src="https://github.com/user-attachments/assets/88fa0896-f122-421a-9f1b-210438b8c987" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
