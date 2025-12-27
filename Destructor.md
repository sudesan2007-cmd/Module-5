# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```class Demo:
    def __init__(self):
        print ("Alive")
    def __del__(self):
        print("The object no longer exists")
obj=Demo()
```

## 🧪 Output
<img width="595" height="163" alt="486522941-45257350-6528-45f1-bd76-344cd37d6330" src="https://github.com/user-attachments/assets/015686a1-c7e6-45ba-a851-845361e3a258" />

## Result
Thus the output is verified.

