# Data Types & Expressions - AP-Style Practice Questions

## Instructions
- Each question focuses on data types, type conversion, operator precedence, and expression evaluation
- Pay attention to integer vs float division, string operations, and type mixing
- Remember order of operations: parentheses, exponents, multiplication/division (left to right), addition/subtraction (left to right)
- Time: 15 minutes (approximately 30 seconds per question)

---

## Section 1: Integer vs Float Operations (Questions 1-8)

**Question 1**
```python
result = 7 / 2
```
What is the value and type of `result`?

A) 3, int  
B) 3.5, float  
C) 3, float  
D) 4, int

---

**Question 2**
```python
result = 7 // 2
```
What is the value and type of `result`?

A) 3, int  
B) 3.5, float  
C) 3, float  
D) 4, int

---

**Question 3**
```python
answer = 10 / 4 + 2
```
What is the value of `answer`?

A) 2  
B) 3  
C) 4.5  
D) 5

---

**Question 4**
```python
value = 15 // 4 * 2
```
What is the value of `value`?

A) 1  
B) 6  
C) 7  
D) 7.5

---

**Question 5**
```python
x = 9 % 4
```
What is the value of `x`?

A) 0  
B) 1  
C) 2  
D) 2.25

---

**Question 6**
```python
result = 5 + 3 * 2
```
What is the value of `result`?

A) 10  
B) 11  
C) 13  
D) 16

---

**Question 7**
```python
answer = (5 + 3) * 2
```
What is the value of `answer`?

A) 10  
B) 11  
C) 13  
D) 16

---

**Question 8**
```python
value = 20 / 4 / 2
```
What is the value of `value`?

A) 2.5  
B) 5.0  
C) 10.0  
D) 2

---

## Section 2: String Operations (Questions 9-16)

**Question 9**
```python
text = "Hello" + "World"
```
What is the value of `text`?

A) "Hello World"  
B) "HelloWorld"  
C) "Hello+World"  
D) Error

---

**Question 10**
```python
message = "Python" * 3
```
What is the value of `message`?

A) "Python3"  
B) "PythonPythonPython"  
C) "Python Python Python"  
D) Error

---

**Question 11**
```python
word = "Code"
result = word + 123
```
What happens when this code executes?

A) result = "Code123"  
B) result = 123  
C) result = "Code 123"  
D) Error - cannot concatenate string and int

---

**Question 12**
```python
text = "AP" + " " + "CS"
```
What is the value of `text`?

A) "APCS"  
B) "AP CS"  
C) "AP + CS"  
D) Error

---

**Question 13**
```python
repeat = "Ha" * 2 + "!"
```
What is the value of `repeat`?

A) "Ha2!"  
B) "HaHa!"  
C) "Ha!Ha!"  
D) Error

---

**Question 14**
```python
greeting = "Hi" * 3
length = len(greeting)
```
What is the value of `length`?

A) 2  
B) 3  
C) 5  
D) 6

---

**Question 15**
```python
word = "Python"
char = word[0]
```
What is the value of `char`?

A) "P"  
B) "p"  
C) 0  
D) Error

---

**Question 16**
```python
name = "Alice"
result = name[1:4]
```
What is the value of `result`?

A) "Ali"  
B) "lic"  
C) "lice"  
D) "Alice"

---

## Section 3: Type Mixing & Conversion (Questions 17-24)

**Question 17**
```python
value = 5 + 2.0
```
What is the value and type of `value`?

A) 7, int  
B) 7.0, float  
C) 7, float  
D) Error

---

**Question 18**
```python
result = 10 / 2
answer = result + 3
```
What is the value and type of `answer`?

A) 8, int  
B) 8.0, float  
C) 8, float  
D) 13, int

---

**Question 19**
```python
num = int(3.7)
```
What is the value of `num`?

A) 3  
B) 3.7  
C) 4  
D) Error

---

**Question 20**
```python
text = str(42)
result = text + "0"
```
What is the value of `result`?

A) 420  
B) 42  
C) "420"  
D) Error

---

**Question 21**
```python
x = float("3.14")
y = x * 2
```
What is the value of `y`?

A) "3.143.14"  
B) 6.14  
C) 6.28  
D) Error

---

**Question 22**
```python
value = int("5") + int("3")
```
What is the value of `value`?

A) 8  
B) "53"  
C) "8"  
D) Error

---

**Question 23**
```python
a = 7 // 2
b = 7 / 2
result = a + b
```
What is the value and type of `result`?

A) 6, int  
B) 6.5, float  
C) 7, float  
D) 7.0, int

---

**Question 24**
```python
number = "100"
doubled = number * 2
```
What is the value of `doubled`?

A) 200  
B) "200"  
C) "100100"  
D) Error

---

## Section 4: Complex Expressions (Questions 25-30)

**Question 25**
```python
result = 2 ** 3 + 5 * 2
```
What is the value of `result`?

A) 16  
B) 18  
C) 26  
D) 64

---

**Question 26**
```python
value = 100 - 20 * 3 / 2
```
What is the value of `value`?

A) 40.0  
B) 70.0  
C) 80.0  
D) 120.0

---

**Question 27**
```python
answer = (10 + 5) * 2 - 8 / 4
```
What is the value of `answer`?

A) 28.0  
B) 30.0  
C) 32.0  
D) 38.0

---

**Question 28**
```python
x = 17 % 5
y = 17 // 5
z = x + y
```
What is the value of `z`?

A) 3  
B) 4  
C) 5  
D) 6

---

**Question 29**
```python
base = 10
exponent = 2
result = base ** exponent / 5
```
What is the value of `result`?

A) 4  
B) 20  
C) 20.0  
D) 400

---

**Question 30**
```python
a = "5"
b = 3
c = int(a) * b
d = a * b
```
What are the values of `c` and `d`?

A) c = 15, d = 15  
B) c = 15, d = "555"  
C) c = "555", d = 15  
D) Both produce errors

---

## Bonus Section: Conceptual Understanding (Questions 31-35)

**Question 31**
What is the difference between `/` and `//` operators?

A) `/` is for integers, `//` is for floats  
B) `/` always returns a float, `//` returns an integer (floor division)  
C) They are the same in Python  
D) `//` is used for comments

---

**Question 32**
Which expression will produce an integer result?

A) 10 / 2  
B) 10 // 3  
C) 10.0 - 5  
D) 2 ** 0.5

---

**Question 33**
What does the `%` operator do?

A) Calculates percentage  
B) Returns the remainder after division  
C) Divides and rounds up  
D) Converts to a percentage

---

**Question 34**
When mixing integers and floats in an expression, the result is:

A) Always an integer  
B) Always a float  
C) Depends on which comes first  
D) Causes an error

---

**Question 35**
Which operation requires type conversion to avoid an error?

A) 5 + 3.2  
B) "Hello" + " World"  
C) "Age: " + 25  
D) 10 * 2

---

## Answer Key

### Section 1: Integer vs Float Operations
1. **B) 3.5, float** - Single `/` always returns float, even for integers
2. **A) 3, int** - `//` is floor division, returns integer
3. **C) 4.5** - 10/4 = 2.5, then 2.5 + 2 = 4.5
4. **B) 6** - 15//4 = 3, then 3*2 = 6 (left to right)
5. **B) 1** - 9 mod 4 = 1 (remainder when 9 divided by 4)
6. **B) 11** - Multiplication first: 3*2=6, then 5+6=11
7. **D) 16** - Parentheses first: 5+3=8, then 8*2=16
8. **A) 2.5** - Left to right: 20/4=5.0, then 5.0/2=2.5

### Section 2: String Operations
9. **B) "HelloWorld"** - Concatenation joins strings directly
10. **B) "PythonPythonPython"** - String multiplication repeats the string
11. **D) Error** - Cannot use + with string and int without conversion
12. **B) "AP CS"** - Three strings concatenated with space
13. **B) "HaHa!"** - "Ha"*2 = "HaHa", then + "!" = "HaHa!"
14. **D) 6** - "Hi"*3 = "HiHiHi" which has 6 characters
15. **A) "P"** - Index 0 is the first character (uppercase P)
16. **B) "lic"** - Slice from index 1 to 4 (not including 4)

### Section 3: Type Mixing & Conversion
17. **B) 7.0, float** - Adding int and float produces float
18. **B) 8.0, float** - 10/2 = 5.0 (float), 5.0+3 = 8.0 (float)
19. **A) 3** - int() truncates decimal (doesn't round)
20. **C) "420"** - str(42) = "42", "42" + "0" = "420"
21. **C) 6.28** - float("3.14") = 3.14, 3.14*2 = 6.28
22. **A) 8** - Both convert to int, then 5+3 = 8
23. **B) 6.5, float** - a=3 (int), b=3.5 (float), 3+3.5=6.5 (float)
24. **C) "100100"** - String * int repeats the string

### Section 4: Complex Expressions
25. **B) 18** - 2³=8, 5*2=10, 8+10=18 (exponent first, then *, then +)
26. **B) 70.0** - 20*3=60, 60/2=30.0, 100-30.0=70.0
27. **A) 28.0** - (10+5)=15, 15*2=30, 8/4=2.0, 30-2.0=28.0
28. **C) 5** - x=17%5=2, y=17//5=3, z=2+3=5
29. **C) 20.0** - 10²=100, 100/5=20.0 (division returns float)
30. **B) c = 15, d = "555"** - c: int("5")*3=15; d: "5"*3="555"

### Bonus Section: Conceptual
31. **B)** - `/` returns float, `//` returns integer (floor division)
32. **B)** - 10 // 3 = 3 (integer); all others return float
33. **B)** - Modulo operator returns remainder
34. **B)** - Mixed operations promote to float
35. **C)** - Need str(25) or cast 25 to string to concatenate

---

## Key Concepts Reinforced

### Data Types
✓ **int** - Whole numbers (5, -3, 0)
✓ **float** - Decimal numbers (3.14, 2.0)
✓ **str** - Text in quotes ("Hello")

### Division Operators
✓ **`/`** - Regular division, ALWAYS returns float (7/2 = 3.5)
✓ **`//`** - Floor division, returns integer (7//2 = 3)
✓ **`%`** - Modulo, returns remainder (7%2 = 1)

### Type Conversion
✓ **int()** - Converts to integer, truncates decimals
✓ **float()** - Converts to float
✓ **str()** - Converts to string

### String Operations
✓ **`+`** - Concatenation (joins strings)
✓ **`*`** - Repetition (repeats string)
✓ **Cannot mix** strings and numbers without conversion

### Order of Operations (PEMDAS)
1. **P**arentheses: ()
2. **E**xponents: **
3. **M**ultiplication & **D**ivision: *, /, //, % (left to right)
4. **A**ddition & **S**ubtraction: +, - (left to right)

### Type Mixing Rules
✓ int + int = int
✓ float + float = float
✓ **int + float = float** (promotes to float)
✓ int / int = float (division special case)
✓ int // int = int
