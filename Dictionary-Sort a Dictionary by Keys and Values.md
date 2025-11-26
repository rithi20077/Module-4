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
my_dict={5: "apple", 2:"banana",6:"cherry",1:"mango", 3:"grapes",4:"orange"}
sort=sorted(my_dict.keys())
print("Keys are")
for key in sort:
    print(key,end=" ")
```

## Sample Output

<img width="1190" height="110" alt="image" src="https://github.com/user-attachments/assets/f5df7b0f-f87c-4e13-9648-d2c389de3ad0" />


## Result

Thus to write a python program to sort dictionary by keys and values are created and verified successfully.
