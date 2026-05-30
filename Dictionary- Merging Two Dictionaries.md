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
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'d': 40, 'e': 50, 'f': 60}

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)

print("Merged Dictionary:", result)
```

## Output
<img width="649" height="43" alt="image" src="https://github.com/user-attachments/assets/1765d53d-798f-4792-9b65-a42208fbfa85" />

## Result
Thus, the Python program to merge two dictionaries and combine their key-value pairs was executed successfully and the output was verified.
