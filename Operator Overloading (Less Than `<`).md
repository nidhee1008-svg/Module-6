# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. Create a class named `A`.
2. Define the `__init__()` method to initialize the object with a value `a`.
3. Define the `__lt__()` method to overload the `<` operator.
4. Compare `self.a` with `o.a`.
5. If `self.a < o.a`, return `"ob1 is less than ob2"`.
6. Otherwise, return `"ob2 is less than ob1"`.
7. Create two objects `ob1` and `ob2`.
8. Use `print(ob1 < ob2)` to trigger the overloaded `<` operator.

---

## 💻 Program

```python
class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"


ob1 = A(2)
ob2 = A(3)

print(ob1 < ob2)
```

## Output

```text
ob1 is less than ob2
```

## Result

Thus, the Python program to demonstrate operator overloading using the less than operator was executed successfully.
