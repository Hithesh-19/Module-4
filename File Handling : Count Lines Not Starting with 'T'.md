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
ile_content = """This is the first line.
The sun is shining.
Today is a good day.
Another line that does not start with T.
Test case.
"""

with open('story.txt', 'w') as f:
    f.write(file_content)

print("Created 'story.txt' for reading.")
print("---")

try:
    with open('story.txt', 'r') as file:
        
        
        count = 0
        for line in file:
            
            clean_line = line.strip()
            
           
            if clean_line and clean_line[0] != 'T':
           
                count += 1
    print(f"The number of lines that do NOT start with 'T' is: {count}")

except FileNotFoundError:
    print("Error: The file 'story.txt' was not found.")
import os
if os.path.exists('story.txt'):
    os.remove('story.txt')
```

## Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1aa1dfd7-6aaa-4733-8672-a7e04c28b3f6" />



## Result
THus the code executed successfully.
