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
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)

print(result)
```

## Output
<img width="1922" height="1023" alt="image" src="https://github.com/user-attachments/assets/151a78bd-5940-4a4f-99d3-38b790aa2f87" />

## Result
Hence successfully done using VSCODE.
