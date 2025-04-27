# Exp.No:4c
## EXCEPTION HANDLING

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.


### ALGORITHM
1. Take input from the user and split it by commas to form a list `x`.
2. Use a list comprehension to convert each item in `x` to an integer after stripping spaces.
3. Print the list of integers if conversion is successful.
4. Handle `ValueError` if conversion fails (e.g., due to non-numeric input).
5. Print an error message and the original list `x` if an exception occurs.

### PROGRAM

```
try:
    x=input().split(",")
    x=[int(g.strip()) for g in x]
    print(x)
except ValueError:
	print("The grades you entered were in an invalid format.")
	print(x)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/62a4286d-a3ff-4a2c-9061-6ccb99b0e53f)

### RESULT
Thus a python program that uses exception handling is successfully implemented.
