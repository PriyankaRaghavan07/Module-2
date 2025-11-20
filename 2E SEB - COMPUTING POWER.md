# Exp.No:2e  
## SEB - COMPUTING POWER

---

### AIM  
To write a Python program to compute the power of a given number using an appropriate built-in function.

---

### ALGORITHM

1. Begin the program.  
2. Input the base number (`base`) from the user.  
3. Input the exponent number (`exp`) from the user.  
4. Use the built-in `pow()` function to compute the base raised to the power of the exponent.  
5. Print the result using the `print()` function, displaying the power in a formatted output.  
6. Terminate the program.

---

### PROGRAM

```

num = int(input())
sum = 0
for i in range(1, num + 1):
    if i % 2 != 0:
        sum += i

print(f"The sum of the series = {sum}")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/5e6627d7-201a-4a27-9d1f-eacb40d23d00)

### RESULT
Thus the program to calculate the sum of the odd number series from 1 to N using a loop has been implemented and executed successfully.
