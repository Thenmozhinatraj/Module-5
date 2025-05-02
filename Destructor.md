# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```python
class student:
    def __init__(self):
        print("Constructor is called. Student object is created.")

    def __del__(self):
        print("Destructor is called. Student object is deleted.")

# Creating object
s2 = student()

# Deleting object
del s2
```

### OUTPUT

![Screenshot 2025-05-02 124125](https://github.com/user-attachments/assets/8543c576-be26-4249-b378-3aa6269f37a6)

### RESULT
Thus, the program executed successfully and the output is verified.
