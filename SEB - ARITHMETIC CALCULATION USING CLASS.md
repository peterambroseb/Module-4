# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
class saveetha():
    def _init_(self,a,b):
        self.a=a
        self.b=b
    def add(self):
        return self.a+self.b
    def div(self):
        return self.a/self.b
a=int(input())
b=int(input())
obj=saveetha(a,b)
o=1
while o!=0:
    o=int(input())
    if o==1:
        print("Result: ",obj.add())
    elif o==2:
        print("Result: ",round(obj.div()))
    elif o==0:
        print("Exiting!")
    else:
        print("invalid choice")


```

### OUTPUT
![WhatsApp Image 2025-04-28 at 21 00 48_bcbf1eb6](https://github.com/user-attachments/assets/87cdc263-00e8-4034-a45c-ef0f51247f55)

### RESULT
Thus a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div was executed and implemented successfully.
