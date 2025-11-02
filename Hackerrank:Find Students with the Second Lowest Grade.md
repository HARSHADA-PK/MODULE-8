# 🎓 Hackerrank:Python Program to Find Students with the Second Lowest Grade

This program reads student names and their corresponding grades, identifies the **second lowest grade**, and prints the names of all students who have that grade in **alphabetical order**.

---

## 🎯 Aim

To write a Python program to:
- Read a list of students and their grades.
- Identify the second lowest grade.
- Print the names of students who have that grade, sorted alphabetically.

---

## 🧠 Algorithm

1. **Read** an integer `n` representing the number of students.
2. **Read** each student’s name and grade, and store them as a sublist inside a list.
3. **Extract** all the grades and sort them.
4. **Identify** the second lowest grade from the sorted grade list.
5. **Collect** names of all students whose grade matches the second lowest grade.
6. **Sort** the names alphabetically.
7. **Print** each name on a new line.

---

## 💻  Program
```
n=int(input())
lists=[]
for i in range(n):
    name=input()
    marks=float(input())
    list=[name,marks]
    lists.append(list)
grades=sorted(set([grade for name,grade in lists]))
sl=grades[1]
l2=sorted([name for name,grade in lists if grade==sl])
for n in l2:
    print(n)
```

## Output
<img width="809" height="424" alt="image" src="https://github.com/user-attachments/assets/73dbea96-3dcc-4559-9873-e6a2674d9867" />

## Result
The program successfully reads names and marks of students, finds the second lowest mark, and then prints the names of all students having that mark in alphabetical order.


