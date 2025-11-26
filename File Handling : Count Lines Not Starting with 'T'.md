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
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)


def merge_files(file1_path, file2_path, output_file_path):
    with open(file1_path,'r')as file1,open(file2_path,'r')as file2,open(output_file_path,'w')as output_file_path:
        output_file_path.write(file1.read())
        output_file_path.write(file2.read())


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
```

## Output

<img width="1012" height="481" alt="image" src="https://github.com/user-attachments/assets/de054fa9-f60e-4f04-b9f7-8152b768e0bd" />


## Result

Thus to write a program to merge two files into a third file is created and executed successfully.

