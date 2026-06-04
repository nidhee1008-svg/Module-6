# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. Create a class named `Rectangle`.
2. Define two private attributes: `__length` and `__breadth`.
3. Use the `__init__()` constructor to initialize the private attributes.
4. Display the private variables from within the class.
5. Create an object of the `Rectangle` class to execute the program.

---

## 💻 Program

```python
class Rectangle:
    def __init__(self):
        self.__length = 10
        self.__breadth = 5
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

obj = Rectangle()
```

## Output

```text
Length: 10
Breadth: 5
```

## Result

Thus, the Python program to demonstrate encapsulation using private members was executed successfully.
