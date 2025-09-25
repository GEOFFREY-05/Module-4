# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
def returnSum(myDict):  <br />
    final=0  <br />
    for i in myDict.values():  <br />
        final+=i  <br />
    return final  <br />
#driver functions  <br />

myDict = {'a': 100, 'b': 200, 'c': 300}  <br />
print("Sum :",returnSum(myDict))

## Output
<img width="395" height="167" alt="image" src="https://github.com/user-attachments/assets/309194be-eef0-431a-91ea-9f321db9ddbd" />

## Result
Thus,the program has been executed successfully
