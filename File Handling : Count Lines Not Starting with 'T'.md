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
f=open("story.txt","r") 
count=0 
for lines in f: 
if lines [0] not in 'T': 
count+=1 
print(count)
```

## Output
![5](https://github.com/user-attachments/assets/06f35d84-135c-40e0-8cfc-e7e507e89e1d)


## Result
 Thus, the program has been successfully executed. 
