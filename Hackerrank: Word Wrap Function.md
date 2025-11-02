# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


## 🧪 Program
```
def wrap(str,n):
    result=''
    for i in range(0,len(str),n):
        result+=str[i:i+n]+'\n'
    return result.rstrip()
            
string=input()
max_width=int(input())
    
```

## Sample Output
<img width="950" height="314" alt="image" src="https://github.com/user-attachments/assets/e566f097-ee43-406b-aea9-da8903289b68" />


## Result
The program successfully formats the given string so that each line contains at most the specified number of characters and displays the wrapped text with proper line breaks.

