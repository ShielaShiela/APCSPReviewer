# 🐍 Python Basics & Object-Oriented Programming
## Fill-in-the-Blank Exam — Set 2

---

**Name:** ________________________________  
**Date:** ________________________________  
**Score:** _______ / 20

> **Instructions:** Fill in each blank with the correct Python keyword, built-in function, method name, or value. Each item is worth **1 point**.

---

### Section A: Python Basics — Data Types & Variables (Q1–Q4)

**1.** The function used to find out the **data type** of a variable is `________`.

```python
x = 42
print(________(x))   # <class 'int'>
```

---

**2.** Python uses `________` for integer division (returns only the whole number, no decimal).

```python
result = 17 ________ 3   # result is 5
```

---

**3.** A **list** is mutable, but a `________` is an immutable sequence that uses parentheses `()`.

```python
my_list  = [1, 2, 3]     # list
my_____  = (1, 2, 3)     # ________
```

---

**4.** To convert the string `"25"` into an integer, you use the built-in function `________`.

```python
age = ________("25")
print(age + 5)   # 30
```

---

### Section B: Python Basics — Control Flow & Functions (Q5–Q8)

**5.** The keyword used to exit a loop **immediately** is `________`.

```python
for i in range(10):
    if i == 5:
        ________   # stops the loop when i is 5
```

---

**6.** The keyword used to **skip** the current iteration and move to the next one is `________`.

```python
for i in range(5):
    if i == 2:
        ________   # skips when i is 2
    print(i)
```

---

**7.** A function that calls **itself** is called a `________` function. Fill in the blank to complete this factorial example:

```python
def factorial(n):
    if n == 1:
        return 1
    return n * ________(n - 1)
```

---

**8.** The keyword `________` is used inside a function to send a value back to the caller.

```python
def square(n):
    ________ n * n

result = square(4)   # result is 16
```

---

### Section C: Python Basics — Lists, Strings & Dictionaries (Q9–Q11)

**9.** To add an element to the **end** of a list, use the `________` method.

```python
fruits = ["apple", "banana"]
fruits.________(  "cherry")
print(fruits)   # ["apple", "banana", "cherry"]
```

---

**10.** To get the **number of characters** in a string (or number of items in a list), use `________`.

```python
name = "Python"
print(________(name))   # 6
```

---

**11.** To access the value associated with the key `"age"` in a dictionary, fill in the blank:

```python
person = {"name": "Ana", "age": 21}
print(person[________])   # 21
```

---

### Section D: OOP — Classes & Objects (Q12–Q15)

**12.** Complete the class so that `Dog("Rex").name` returns `"Rex"`:

```python
class Dog:
    def __init__(________, name):
        ________.name = name
```

*(Both blanks use the same word.)*

---

**13.** A **class attribute** belongs to the class itself, not to any one instance. Fill in the missing value so all `Circle` objects share the same `pi`:

```python
class Circle:
    ________ = 3.14159   # class attribute

    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return Circle.________ * self.radius ** 2
```

*(Both blanks use the same word.)*

---

**14.** The `________` method is called when `print()` is used on an object, and should return a **string**.

```python
class Book:
    def __init__(self, title):
        self.title = title

    def ________(self):
        return f"Book title: {self.title}"

b = Book("Fluent Python")
print(b)   # Book title: Fluent Python
```

---

**15.** To check if `my_cat` is an instance of the `Cat` class, use:

```python
my_cat = Cat("Whiskers")
print(________(my_cat, Cat))   # True
```

---

### Section E: OOP — Inheritance & Polymorphism (Q16–Q18)

**16.** Fill in the blank so `GuideDog` inherits from `Dog`:

```python
class Dog:
    def speak(self):
        print("Woof!")

class GuideDog(________):
    pass

g = GuideDog()
g.speak()   # Woof!
```

---

**17.** Use `________` to call the **parent class's constructor** from inside the child class:

```python
class Vehicle:
    def __init__(self, brand):
        self.brand = brand

class Car(Vehicle):
    def __init__(self, brand, model):
        ________.__init__(brand)
        self.model = model
```

---

**18.** When a child class defines a method with the **same name** as the parent, the child's version **`________`** the parent's version.

```python
class Animal:
    def sound(self):
        print("...")

class Duck(Animal):
    def sound(self):          # this ________ the parent method
        print("Quack!")
```

---

### Section F: OOP — Encapsulation & Special Methods (Q19–Q20)

**19.** A method decorated with `@staticmethod` does **not** receive `________` or `cls` — it behaves like a regular function inside a class.

```python
class Temperature:
    @staticmethod
    def celsius_to_fahrenheit(c):
        return c * 9/5 + 32

# Called without creating an instance:
print(Temperature.celsius_to_fahrenheit(100))   # 212.0
```

---

**20.** The dunder method `________` defines the behavior of the `+` operator between two objects.

```python
class Vector:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def ________(self, other):
        return Vector(self.x + other.x, self.y + other.y)

v1 = Vector(1, 2)
v2 = Vector(3, 4)
v3 = v1 + v2   # uses the dunder method above
```

---
---

# ✅ ANSWER KEY

| # | Answer |
|---|--------|
| 1 | `type` |
| 2 | `//` |
| 3 | `tuple` |
| 4 | `int` |
| 5 | `break` |
| 6 | `continue` |
| 7 | `recursive` / `factorial` *(function name)* |
| 8 | `return` |
| 9 | `append` |
| 10 | `len` |
| 11 | `"age"` |
| 12 | `self` *(both blanks)* |
| 13 | `pi` *(both blanks)* |
| 14 | `__str__` |
| 15 | `isinstance` |
| 16 | `Dog` |
| 17 | `super()` |
| 18 | `overrides` |
| 19 | `self` |
| 20 | `__add__` |

---

*End of Exam — You've got this! 💪🐍*
