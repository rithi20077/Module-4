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
```
try:
    n=int(input())
    a=[]
    for i in range(1,n+1):
        elem=int(input())
        a.append(elem)
    print(a)
    index=6
    print(a[index])
except:
    print(f"{index} is not accepted")
```

## Output

<img width="717" height="443" alt="image" src="https://github.com/user-attachments/assets/15ceb6f1-8c26-415a-81c2-d4cbdcfccecc" />


## Result

Thus to write a Python Program that handles an IndexError when trying to access an element beyond the available range of a list is created and verified successfully.
