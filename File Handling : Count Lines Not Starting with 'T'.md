# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0

file = open("story.txt", "r")

for line in file:
    if line[0] != 'T':
        count += 1

file.close()

print("Number of lines not starting with T:", count)
```

## Output
<img width="359" height="51" alt="image" src="https://github.com/user-attachments/assets/cb5af61f-c808-4d00-a12b-f197fcb1b2cd" />

## Result
Thus, the Python program to count the number of lines in the file story.txt that do not start with the alphabet 'T' was executed successfully and the output was verified.
