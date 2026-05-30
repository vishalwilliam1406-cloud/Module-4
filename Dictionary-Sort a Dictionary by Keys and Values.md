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
dictionary = {
    'c': 'orange',
    'a': 'apple',
    'b': 'banana'
}

sorted_keys = dict(sorted(dictionary.items()))

sorted_values = dict(
    sorted(dictionary.items(), key=lambda item: item[1])
)

print("Original Dictionary:", dictionary)
print("Sorted by Keys:", sorted_keys)
print("Sorted by Values:", sorted_values)
```

## Sample Output
<img width="595" height="152" alt="image" src="https://github.com/user-attachments/assets/0376f7a6-334a-4c6b-b33c-91eb29f83577" />

## Result
Thus, the Python program to sort a dictionary by its keys and values was executed successfully and the output was verified.
