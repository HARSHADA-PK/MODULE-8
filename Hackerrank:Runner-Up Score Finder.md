# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```
n = int(input())            
arr = list(map(int, input().split()))  

unique_scores = list(set(arr))
unique_scores.sort()
print(unique_scores[-2])
```

## OUTPUT
<img width="655" height="191" alt="image" src="https://github.com/user-attachments/assets/10d19904-7866-49e8-9234-d7c49a75f121" />

## RESULT
The program successfully reads a list of scores, removes duplicates, sorts them in ascending order, and prints the second highest score from the list.
