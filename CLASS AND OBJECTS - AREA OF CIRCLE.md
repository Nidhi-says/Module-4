# Exp.No:4a  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `stationary`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `pen`.  
3. Define a method `stationary(self, a)` inside the class `pen` that accepts a radius `a` as an argument.  
4. Inside the `stationary` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times a^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `pen` class and store it in the variable `obj`.  
7. Call the `stationary` method of the `pen` class, passing the user-provided radius `a` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
class pen:
    def __init__(self,a):
        self.a=a
    def dis(self):
        print("Area of circle: {:.2f}".format(3.141592*self.a*self.a))
a=int(input())
obj=pen(a)
obj.dis()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/04d8af2c-3202-4694-8d88-be7908f1310e)



### RESULT
Thus a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `stationary` is implemented.


