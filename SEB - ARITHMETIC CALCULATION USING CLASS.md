# Exp.No:4e
## SEB - RETURN A DICTIONARY

### AIM  
To write a python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n!

### ALGORITHM

1. Take an integer input `a` from the user.
2. Initialize an empty dictionary `d` and a variable `f` with value `1`.
3. Loop from `1` to `a-1`, multiplying `f` by the current number `i` at each step.
4. Store each `i` as a key and its corresponding factorial `f` as the value in dictionary `d`.
5. Print the final dictionary `d` showing numbers and their factorials.


### PROGRAM

```
a=int(input())
d={}
f=1
for i in range(1,a):
    f*=i
    d[i]=f
print("The obtained dictionary is d = ",d)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/63a3fa2f-350a-411f-b7f0-4eda8b1ad23a)

### RESULT
Thus a python program that asks the user to enter an integer n and return a dictionary is implemented successfully.
