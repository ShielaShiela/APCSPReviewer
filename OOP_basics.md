# 🐍 Object-Oriented Programming in Python
## Basics Exam with Review

---

# 📚 PART 1: REVIEW NOTES

> Read this carefully before attempting the exam!

---

## 1. What is OOP?

**Object-Oriented Programming (OOP)** is a programming paradigm that organizes code around **objects** — instances of **classes** that bundle together data (attributes) and behavior (methods).

---

## 2. Core Concepts

### 🔷 Class
A **class** is a blueprint or template for creating objects.

```python
class Dog:
    pass
```

### 🔷 Object / Instance
An **object** is a specific instance created from a class.

```python
my_dog = Dog()  # 'my_dog' is an object of class Dog
```

---

### 🔷 `__init__` Method (Constructor)
The `__init__` method is automatically called when an object is created. It initializes the object's attributes.

```python
class Dog:
    def __init__(self, name, age):
        self.name = name   # instance attribute
        self.age = age
```

---

### 🔷 `self`
`self` refers to the **current instance** of the class. It must be the first parameter of every instance method.

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} says: Woof!")
```

---

### 🔷 Attributes
| Type | Description | Example |
|------|-------------|---------|
| **Instance attribute** | Belongs to a specific object | `self.name = name` |
| **Class attribute** | Shared by all instances | `species = "Canis familiaris"` |

```python
class Dog:
    species = "Canis familiaris"   # class attribute

    def __init__(self, name):
        self.name = name           # instance attribute
```

---

### 🔷 Methods
A **method** is a function defined inside a class.

```python
class Circle:
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius ** 2
```

---

## 3. The 4 Pillars of OOP

### 🏛️ Encapsulation
Bundling data and methods together, and restricting direct access using **private** attributes (prefixed with `_` or `__`).

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance   # private attribute

    def get_balance(self):
        return self.__balance      # accessed via method (getter)
```

---

### 🏛️ Inheritance
A **child class** inherits attributes and methods from a **parent class** using the syntax `class Child(Parent)`.

```python
class Animal:
    def speak(self):
        print("Some sound")

class Cat(Animal):
    def speak(self):            # overrides parent method
        print("Meow!")
```

---

### 🏛️ Polymorphism
The ability of different objects to respond to the **same method call** in different ways.

```python
class Bird:
    def move(self):
        print("Flying")

class Fish:
    def move(self):
        print("Swimming")

for animal in [Bird(), Fish()]:
    animal.move()   # each responds differently
```

---

### 🏛️ Abstraction
Hiding complex implementation details and exposing only the necessary interface. In Python, this is done using the `abc` module.

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass
```

---

## 4. Key Keywords & Functions

| Keyword / Function | Purpose |
|-------------------|---------|
| `class` | Defines a class |
| `self` | Refers to the current instance |
| `__init__` | Constructor method |
| `super()` | Calls the parent class's method |
| `isinstance()` | Checks if an object is an instance of a class |
| `issubclass()` | Checks if a class is a subclass of another |
| `@property` | Creates a getter method |
| `@staticmethod` | Defines a method that doesn't use `self` |
| `@classmethod` | Defines a method that receives the class as first argument |

---

## 5. Quick Reference: Class Template

```python
class ClassName:
    class_attribute = "shared value"

    def __init__(self, param1, param2):
        self.param1 = param1    # instance attribute
        self.param2 = param2

    def instance_method(self):
        return self.param1

    @classmethod
    def class_method(cls):
        return cls.class_attribute

    @staticmethod
    def static_method():
        return "No self or cls needed"
```

---

## 6. `super()` in Inheritance

```python
class Animal:
    def __init__(self, name):
        self.name = name

class Dog(Animal):
    def __init__(self, name, breed):
        super().__init__(name)   # calls Animal's __init__
        self.breed = breed
```

---

## 7. Dunder (Magic) Methods

| Method | Triggered by |
|--------|-------------|
| `__init__` | Object creation |
| `__str__` | `print(obj)` or `str(obj)` |
| `__repr__` | `repr(obj)` |
| `__len__` | `len(obj)` |
| `__eq__` | `obj1 == obj2` |
| `__add__` | `obj1 + obj2` |

```python
class Book:
    def __init__(self, title):
        self.title = title

    def __str__(self):
        return f"Book: {self.title}"
```

---
---

# ✏️ PART 2: EXAM

**Name:** ________________________________  
**Date:** ________________________________  
**Score:** _______ / 20

> **Instructions:** Fill in each blank with the correct Python keyword, method name, or code. Each item is worth **1 point**.

---

### Section A: Classes and Objects (Q1–Q5)

**1.** The keyword used to define a class in Python is `________`.

```python
________ Animal:
    pass
```

---

**2.** To create an **instance** of the `Animal` class, you write:

```python
my_animal = ________()
```

---

**3.** The special method that is automatically called when an object is created is called `________`.

```python
class Car:
    def ________(self, brand):
        self.brand = brand
```

---

**4.** The first parameter of every **instance method** must be `________`, which refers to the current object.

```python
class Student:
    def greet(________):
        print("Hello!")
```

---

**5.** A **class attribute** is shared by all instances. Fill in the blank to define one:

```python
class Dog:
    ________ = "Canis familiaris"   # class attribute

    def __init__(self, name):
        self.name = name            # instance attribute
```

---

### Section B: Encapsulation (Q6–Q8)

**6.** To make an attribute **private** in Python, prefix its name with `________`.

```python
class BankAccount:
    def __init__(self, balance):
        self.________balance = balance   # private attribute
```

---

**7.** To allow read-only access to a private attribute, you can use the `________` decorator.

```python
class Person:
    def __init__(self, age):
        self.__age = age

    @________
    def age(self):
        return self.__age
```

---

**8.** Complete the `get_balance` method so it returns the private `__balance` attribute:

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance

    def get_balance(self):
        return self.________
```

---

### Section C: Inheritance (Q9–Q12)

**9.** To make `Dog` inherit from `Animal`, fill in the blank:

```python
class Animal:
    pass

class Dog(________):
    pass
```

---

**10.** To call the **parent class's `__init__`** method from a child class, use `________`.

```python
class Animal:
    def __init__(self, name):
        self.name = name

class Dog(Animal):
    def __init__(self, name, breed):
        ________.__init__(name)
        self.breed = breed
```

---

**11.** When a child class defines a method with the **same name** as in the parent class, this is called method `________`.

---

**12.** The built-in function `________` checks whether an object is an instance of a particular class.

```python
my_dog = Dog("Rex", "Labrador")
print(________(my_dog, Dog))   # True
```

---

### Section D: Polymorphism & Abstraction (Q13–Q16)

**13.** **Polymorphism** allows different classes to define the **same method name** with different behaviors. Fill in the missing method name:

```python
class Cat:
    def ________(self):
        print("Meow")

class Dog:
    def ________(self):
        print("Woof")
```

*(Both blanks are the same word — you choose the method name that makes sense for both animals to share.)*

---

**14.** To create an **abstract class** in Python, import from this module: `________`.

```python
from ________ import ABC, abstractmethod
```

---

**15.** An **abstract method** is decorated with `________`.

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @________
    def area(self):
        pass
```

---

**16.** A class that inherits from `ABC` and contains `@abstractmethod` **cannot be `________`** directly — you must use a subclass that implements all abstract methods.

---

### Section E: Special Methods & Static/Class Methods (Q17–Q20)

**17.** The dunder method `________` is called when you use `print()` on an object.

```python
class Book:
    def __init__(self, title):
        self.title = title

    def ________(self):
        return f"Book: {self.title}"
```

---

**18.** A **static method** is decorated with `________` and does not receive `self` or `cls`.

```python
class MathUtils:
    @________
    def add(a, b):
        return a + b
```

---

**19.** A **class method** receives `________` as its first argument instead of `self`.

```python
class Counter:
    count = 0

    @classmethod
    def increment(________):
        ________.count += 1
```

*(Both blanks use the same word.)*

---

**20.** The dunder method used to define behavior for the `==` operator is `________`.

```python
class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def ________(self, other):
        return self.x == other.x and self.y == other.y
```

---
---

# ✅ ANSWER KEY

| # | Answer |
|---|--------|
| 1 | `class` |
| 2 | `Animal` |
| 3 | `__init__` |
| 4 | `self` |
| 5 | `species` *(any valid variable name)* |
| 6 | `__` *(double underscore)* |
| 7 | `property` |
| 8 | `__balance` |
| 9 | `Animal` |
| 10 | `super()` |
| 11 | `overriding` |
| 12 | `isinstance` |
| 13 | `speak` *(or any consistent method name)* |
| 14 | `abc` |
| 15 | `abstractmethod` |
| 16 | `instantiated` |
| 17 | `__str__` |
| 18 | `@staticmethod` |
| 19 | `cls` |
| 20 | `__eq__` |

---

*End of Exam — Good luck! 🎉*
