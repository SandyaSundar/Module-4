## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = eval(input())
dict2 = eval(input())

merged_dict = dict2.copy()
merged_dict.update(dict1)

print(merged_dict)
```

## Output
<img width="1243" height="822" alt="image" src="https://github.com/user-attachments/assets/dd8dd18c-471f-4d70-9ceb-edcd333f2896" />

## Result
Thus the given python program has been executed successfully.
