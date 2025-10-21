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
dict1 = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}

dict2 = {
    "age": 31,  
    "job": "Engineer",
    "city": "San Francisco" 
}


def merge(d1, d2):
    
    merged_dict = {**d1, **d2}
    return merged_dict


merged_result = merge(dict1, dict2)

print("---")
print(f"Dictionary 1 (dict1): {dict1}")
print(f"Dictionary 2 (dict2): {dict2}")
print("---")
print(f"Merged Dictionary: {merged_result}")
print("---")
```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-21 122011" src="https://github.com/user-attachments/assets/c2cabed5-90e1-4049-9ad3-f1065aa9fd92" />

## Result
Thus the python program that merges **two dictionaries** and combines their key-value pairs executed successfully.

