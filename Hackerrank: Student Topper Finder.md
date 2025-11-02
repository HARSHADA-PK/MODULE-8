# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
```
dicts=eval(input())
dict1={name:sum(lists) for name,lists in dicts.items()}
m=max(dict1,key=dict1.get)
score=dict1[m]
print(dict1)
print("Topper is: ",m,"with marks = ",score)
```

## OUTPUT
<img width="1043" height="197" alt="image" src="https://github.com/user-attachments/assets/9a5dfe47-f7bb-4e4e-b419-d2cc4011849f" />


## RESULT
Thus, the program has executed successfully.
