# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
def create_multiples_of_5_tuple(N):
    multiples_of_5 = tuple(range(5, N , 5))
    return multiples_of_5

if __name__ == "__main__":
    N = int(input())

    result_tuple = create_multiples_of_5_tuple(N)
    print(result_tuple)

```

### OUTPUT
<img width="1183" height="241" alt="image" src="https://github.com/user-attachments/assets/485c37a1-1535-4d6c-8362-c4b69bf42407" />

### RESULT
Thus, the Python program to create a tuple containing all multiples of 5 up to a given number N has been implemented and executed successfully.
