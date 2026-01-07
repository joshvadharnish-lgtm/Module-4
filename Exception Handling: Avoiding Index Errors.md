# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 
🧾 Program
```
l=['laptop','mobile','pen']
try:
    print(l[4])
except IndexError:
        print('check index range')
```
## Output
![WhatsApp Image 2026-01-07 at 3 18 56 PM](https://github.com/user-attachments/assets/cda8de9d-3f56-4136-8164-cb48e7426c80)

## Result
Thus,the program has been executed successfully
