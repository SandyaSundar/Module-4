# File Handling in Python: Count the frequency of each character

## 🎯 Aim
To write a Python program to read a file and count the frequency of each character in it.
## 🧠 Algorithm
1. Open the file in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file and increment the `count` by 1 if there is an increase in frequency
4. After processing all lines, print the `count` value

## 🧾 Program
```
from collections import defaultdict


def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def char_frequency(file_path):
   freq = defaultdict(int)
   
   with open(file_path, 'r') as file:
       content = file.read()
       
       for char in content:
           freq[char] += 1
           
   return freq       
```

## Output
<img width="1895" height="898" alt="image" src="https://github.com/user-attachments/assets/3403c5f4-ac96-411c-8a1c-8dc0ebd78033" />

## Result
Thus the given python program has been executed successfully.
