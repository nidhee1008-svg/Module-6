# 🐍 Python OOP: Polymorphism with Classes

## AIM

To create two classes, `Beans` and `Mango`, and demonstrate polymorphism using a generic function that identifies the type and color of the objects.

## ALGORITHM

1. Create a class `Beans`.
2. Define the method `type()` to display "Vegetable".
3. Define the method `color()` to display "Green".
4. Create a class `Mango`.
5. Define the method `type()` to display "Fruit".
6. Define the method `color()` to display "Yellow".
7. Define a generic function `func(obj)` that calls `obj.type()` and `obj.color()`.
8. Create objects of `Beans` and `Mango`.
9. Pass the objects to the function `func()`.
10. Display the output.

## PROGRAM

```python
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


def func(obj):
    obj.type()
    obj.color()


b = Beans()
m = Mango()

func(b)
func(m)
```

## OUTPUT

```text
Vegetable
Green
Fruit
Yellow
```

## RESULT

Thus, the Python program to demonstrate polymorphism using the classes `Beans` and `Mango` was successfully executed, and the expected output was obtained.
