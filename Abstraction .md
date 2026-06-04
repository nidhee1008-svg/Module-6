# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. Import `ABC` and `abstractmethod` from the `abc` module.
2. Create an abstract class named `Shape`.
3. Define an abstract method named `calculate_area()`.
4. Create a subclass named `Rectangle`.
5. Set default values for `length` and `breadth`.
6. Override `calculate_area()` to compute and print the rectangle area.
7. Create a subclass named `Circle`.
8. Set a default value for `radius`.
9. Override `calculate_area()` to compute and print the circle area.
10. Create objects for `Rectangle` and `Circle`.
11. Call their `calculate_area()` methods.

---

## 💻 Program

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def calculate_area(self):
        pass


class Rectangle(Shape):
    def __init__(self):
        self.length = 10
        self.breadth = 5

    def calculate_area(self):
        area = self.length * self.breadth
        print("Area of rectangle:", area)


class Circle(Shape):
    def __init__(self):
        self.radius = 7

    def calculate_area(self):
        area = 3.14 * self.radius * self.radius
        print("Area of circle:", area)


rect = Rectangle()
circle = Circle()

rect.calculate_area()
circle.calculate_area()
```

## Output

```text
Area of rectangle: 50
Area of circle: 153.86
```

## Result

Thus, the Python program to demonstrate abstraction using an abstract class and abstract method was executed successfully.
