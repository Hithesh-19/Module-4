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
my_dict = {
    "banana": 3,
    "apple": 1,
    "cherry": 2,
    "date": 4,
    "elderberry": 5
}
print("Original Dictionary:")
print(my_dict)

sorted_by_key_list = sorted(my_dict.items())
sorted_by_key_dict = dict(sorted_by_key_list)


sorted_by_value_list = sorted(my_dict.items(), key=lambda item: item[1])
sorted_by_value_dict = dict(sorted_by_value_list)
print("Dictionary Sorted by Keys:")

print(sorted_by_key_dict)

print("\n---")
print("Dictionary Sorted by Values:")
print(sorted_by_value_dict)
print("---")
```

## Sample Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/19c9b338-58ab-4e02-b520-a669e4f24755" />

## Result

program  executed  successfully.
