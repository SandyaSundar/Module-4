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
```
dict1 = {2:56,1:2,5:12,4:24,6:18,3:323}
sorted_dict = sorted(dict1.items())
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_dict:
    print(f"({key}, {value})", end = " ")
```

## Sample Output
<img width="1325" height="898" alt="image" src="https://github.com/user-attachments/assets/de43f093-e290-440a-a1b2-5db48358bc1a" />

## Result
Thus the python program has been executed successfully.
