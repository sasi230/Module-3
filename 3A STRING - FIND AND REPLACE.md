# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```

def convert(a):
    new=""
    for i in range(0,len(a)):
        if a[i].isupper():
            new+=a[i].lower()
        elif a[i].islower():
            new+=a[i].upper()
        else:
            new+="bb"
    print(new)
            
```

### OUTPUT
<img width="837" height="282" alt="image" src="https://github.com/user-attachments/assets/a0fb1630-7b60-43b8-b49c-5f256c99b838" />


### RESULT
Thus, the Python program to convert uppercase to lowercase, lowercase to uppercase, and replace special characters with "bb" has been implemented and executed successfully.
