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
d = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

# Sort by keys
sorted_keys = dict(sorted(d.items()))

# Sort by values
sorted_values = dict(sorted(d.items(), key=lambda x: x[1]))

print("Sorted by keys:", sorted_keys)
print("Sorted by values:", sorted_values)
```
## Sample Output
<img width="1922" height="1029" alt="image" src="https://github.com/user-attachments/assets/bc44c1b3-72a7-4f87-a664-b43e8605a454" />

## Result
Hence successfully done using VSCODE.
