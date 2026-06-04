# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`.
3. Override the `type()` method in the `Shark` class to print `"shark"`.
4. Create an instance of the `Fish` class named `obj_goldfish`.
5. Create an instance of the `Shark` class named `obj_hammerhead`.
6. Use a `for` loop to iterate over both objects.
7. Within the loop, call the `type()` method using the loop variable.
8. Display the output to demonstrate method overriding.

## 💻 PROGRAM:

```python
class Fish:
    def type(self):
        print("fish")


class Shark(Fish):
    def type(self):
        print("shark")


obj_goldfish = Fish()
obj_hammerhead = Shark()

for animal in (obj_goldfish, obj_hammerhead):
    animal.type()
```

## OUTPUT

```text
fish
shark
```

## RESULT

Thus, the Python program to demonstrate method overriding was executed successfully.
