
# Exception Handling in Python: Avoiding Index Errors

## Name   : Austin Aro A
## Reg No : 212224040038

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
msg=[5, 10, 20]
try:
    print(msg[5])
except IndexError:
    print("You're out of list range")
```
## Output
![4 4](https://github.com/user-attachments/assets/1045520c-73d5-4a17-9523-29e49f2a07bc)

## Result
Thus,the program has been executed successfully.
