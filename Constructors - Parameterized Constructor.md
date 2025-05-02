# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```python
class person:
    def __init__(self, name, userid):
        self.name = name
        self.userid = userid
        print("User ID is:", self.userid)

name = input("Enter your name: ")
userid = input("Enter your userid: ")

s1 = person(name, userid)
```

### OUTPUT
![Screenshot 2025-05-02 123814](https://github.com/user-attachments/assets/138efd9e-f814-4f0d-95db-4d19a9860799)

### RESULT
Thus, the program executed successfully and the output is verified.
