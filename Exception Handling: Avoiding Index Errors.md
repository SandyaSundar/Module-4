# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[6]`).
   - In the `except` block, catch the error and print a custom message `"6 is not accepted"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
numbers = []
n = int(input())
for i in range(n):
    num = int(input())
    numbers.append(num)
print(numbers)
try:
    print(numbers[6])
except IndexError:
    print("6 is not accepted")
```

## Output
<img width="617" height="912" alt="image" src="https://github.com/user-attachments/assets/20692662-6377-46ea-a491-fa37e6839121" />

## Result
Thus the given python program has been executed successfully.
