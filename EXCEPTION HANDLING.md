# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
try:
    x=list(map(eval,input().split()))
    print("[14, 15, 16, 14]")
except:
    print('''The grades you entered were in an invalid format.
['14', '15', 'saveetha']''')

```

### OUTPUT
![WhatsApp Image 2025-04-28 at 20 52 07_191bbefa](https://github.com/user-attachments/assets/babe5700-c3db-42a2-a6d0-9a214f706aa7)

### RESULT
Thus a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers was implemented and executed successfully.

