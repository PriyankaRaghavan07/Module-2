# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```

a = int(input())
for i in range(1, a + 1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print(end="\n")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/2769b95f-5e19-4b03-8cd2-8d09219dd840)

### RESULT
Thus the program to print a pyramid pattern of numbers based on the number of rows entered by the user has been implemented and executed successfully.
