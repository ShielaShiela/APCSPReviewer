# AP Computer Science A Exam Review (Python Edition)
## Part A: Strings | Part B: Functions

---

# Part A: Strings (Questions 1-20)

## Multiple Choice Questions

### Question 1
What is the output of the following code?
```python
s = "Computer"
print(s[3:6])
```

A) `put`  
B) `mpu`  
C) `pute`  
D) `mput`  

---

### Question 2
What is the value of `result` after executing this code?
```python
word = "programming"
result = word.find("m")
```

A) `5`  
B) `6`  
C) `7`  
D) `8`  

---

### Question 3
Consider the following code segment:
```python
s = "AP Computer Science"
result = s[:2] + s[3:11]
```
What is the value of `result`?

A) `"APComputer"`  
B) `"AP Computer"`  
C) `"APCompute"`  
D) `"AP Compute"`  

---

### Question 4
What is the output of this code?
```python
s1 = "Hello"
s2 = "Hello"
s3 = "Hel" + "lo"

print(s1 == s2)
print(s1 == s3)
print(s1 is s3)
```

A) `True True True`  
B) `True True False`  
C) `False False True`  
D) `True False False`  

---

### Question 5
What is printed when the following code is executed?
```python
text = "Java"
text + " Programming"
print(text)
```

A) `Java Programming`  
B) `Java`  
C) `Programming`  
D) `None`  

---

### Question 6
What is the output of the following code?
```python
s = "Mississippi"
count = 0
for char in s:
    if char == "s":
        count += 1
print(count)
```

A) `2`  
B) `3`  
C) `4`  
D) `5`  

---

### Question 7
What does `"education"[3:]` return?

A) `"edu"`  
B) `"cation"`  
C) `"ucation"`  
D) `"ation"`  

---

### Question 8
Consider the following code:
```python
name = "Alice"
print(len(name) + name.find("i"))
```
What is the output?

A) `6`  
B) `7`  
C) `8`  
D) `9`  

---

### Question 9
What is the output of the following code?
```python
a = "apple"
b = "banana"
print(a < b)
```

A) `True`  
B) `False`  
C) `0`  
D) Error  

---

### Question 10
What is the output of this code?
```python
s = "APCS"
result = ""
for i in range(len(s) - 1, -1, -1):
    result += s[i]
print(result)
```

A) `APCS`  
B) `SCPA`  
C) `SCP`  
D) `CSPA`  

---

### Question 11
What does the following function return when called with `mystery("hello")`?
```python
def mystery(s):
    result = ""
    for i in range(0, len(s), 2):
        result += s[i]
    return result
```

A) `"hel"`  
B) `"hlo"`  
C) `"elo"`  
D) `"el"`  

---

### Question 12
What is the value of `x` after this code executes?
```python
word = "computer"
x = word.find("z")
```

A) `0`  
B) `-1`  
C) `8`  
D) `None`  

---

### Question 13
Consider the following code:
```python
s = "Python is fun"
s = s[7:]
s = s[:2]
print(s)
```
What is printed?

A) `"is"`  
B) `"Py"`  
C) `"th"`  
D) `"on"`  

---

### Question 14
What is the output of this code segment?
```python
phrase = "hello world"
print(phrase.find("o"), phrase.rfind("o"))
```

A) `4 7`  
B) `4 4`  
C) `7 7`  
D) `7 4`  

---

### Question 15
What does the following code print?
```python
s = ""
for i in range(1, 4):
    s = s + str(i) + str(i)
print(s)
```

A) `123123`  
B) `112233`  
C) `6`  
D) `246`  

---

### Question 16
What is the output of this code?
```python
text = "Hello World"
print(text.lower().count("l"))
```

A) `2`  
B) `3`  
C) `4`  
D) `1`  

---

### Question 17
What does the following code print?
```python
s = "python"
print(s[1:4] + s[-2:])
```

A) `"ython"`  
B) `"ython"`  
C) `"ython"`  
D) `"thoon"`  

---

### Question 18
What is the output?
```python
word = "programming"
print(word.replace("m", "x", 1))
```

A) `"prograxxing"`  
B) `"progra xming"`  
C) `"prograxming"`  
D) `"programmxng"`  

---

### Question 19
What does this code print?
```python
s = "abcdef"
print(s[::2])
```

A) `"abc"`  
B) `"ace"`  
C) `"bdf"`  
D) `"fedcba"`  

---

### Question 20
What is the output?
```python
text = "  hello  "
print(len(text.strip()))
```

A) `9`  
B) `7`  
C) `5`  
D) `8`  

---

## Free Response Questions

### Question 21
Write a function `count_vowels` that takes a string parameter and returns the number of vowels (a, e, i, o, u - case insensitive) in the string.

```python
def count_vowels(s):
    # Your code here
    pass
```

**Sample calls:**
- `count_vowels("Hello World")` returns `3`
- `count_vowels("AEIOU")` returns `5`

---

### Question 22
Write a function `is_palindrome` that takes a string and returns `True` if it reads the same forwards and backwards (case-sensitive), `False` otherwise.

```python
def is_palindrome(s):
    # Your code here
    pass
```

**Sample calls:**
- `is_palindrome("racecar")` returns `True`
- `is_palindrome("hello")` returns `False`

---

### Question 23
Write a function `remove_char` that takes a string and a character, and returns a new string with all occurrences of that character removed.

```python
def remove_char(s, char):
    # Your code here
    pass
```

**Sample calls:**
- `remove_char("hello world", "l")` returns `"heo word"`
- `remove_char("aabbcc", "b")` returns `"aacc"`

---

### Question 24
Write a function `replace_first` that takes three parameters: a string `original`, a string `target`, and a string `replacement`. The function should return a new string where the first occurrence of `target` is replaced with `replacement`. If `target` is not found, return the original string unchanged. **Do not use the built-in replace method.**

```python
def replace_first(original, target, replacement):
    # Your code here
    pass
```

**Sample calls:**
- `replace_first("hello world", "o", "0")` returns `"hell0 world"`
- `replace_first("aaa", "a", "b")` returns `"baa"`

---

### Question 25
Write a function `scramble` that takes two strings of equal length and returns a new string with alternating characters from each string.

```python
def scramble(s1, s2):
    # Precondition: len(s1) == len(s2)
    # Your code here
    pass
```

**Sample calls:**
- `scramble("abc", "XYZ")` returns `"aXbYcZ"`
- `scramble("hi", "12")` returns `"h1i2"`

---

---

# Part B: Functions (Questions 26-40)

## Multiple Choice Questions

### Question 26
What is the output of the following code?
```python
def triple(x):
    return x * 3

num = 5
print(triple(num), num)
```

A) `15 15`  
B) `15 5`  
C) `5 5`  
D) `5 15`  

---

### Question 27
Consider the following function:
```python
def mystery(a, b):
    if a < b:
        return a
    else:
        return b
```
What does `mystery(7, 3) + mystery(3, 7)` evaluate to?

A) `6`  
B) `10`  
C) `14`  
D) `3`  

---

### Question 28
What is the result of calling `calculate(4)`?
```python
def calculate(n):
    if n <= 1:
        return 1
    return n * calculate(n - 1)
```

A) `4`  
B) `10`  
C) `24`  
D) `120`  

---

### Question 29
What does the following function return when called with `process(5)`?
```python
def process(n):
    result = 0
    for i in range(1, n + 1):
        result += i
    return result
```

A) `5`  
B) `10`  
C) `15`  
D) `20`  

---

### Question 30
Consider the following code:
```python
def modify(x):
    x = x + 10
    return x

num = 5
modify(num)
print(num)
```
What is printed?

A) `5`  
B) `10`  
C) `15`  
D) `0`  

---

### Question 31
What is the output of the following code?
```python
def foo(a, b=None):
    if b is None:
        return a * 2
    return a + b

print(foo(3) + foo(2, 3))
```

A) `8`  
B) `11`  
C) `12`  
D) Error  

---

### Question 32
What value is returned by `mystery(12345)`?
```python
def mystery(n):
    count = 0
    while n > 0:
        count += 1
        n = n // 10
    return count
```

A) `3`  
B) `4`  
C) `5`  
D) `15`  

---

### Question 33
What does `power(2, 5)` return?
```python
def power(base, exp):
    if exp == 0:
        return 1
    return base * power(base, exp - 1)
```

A) `10`  
B) `25`  
C) `32`  
D) `64`  

---

### Question 34
What is the output?
```python
def increment(n):
    n += 1
    return n

x = 10
y = increment(x)
print(x, y)
```

A) `10 10`  
B) `11 11`  
C) `10 11`  
D) `11 10`  

---

### Question 35
Consider the following function:
```python
def is_even(n):
    return n % 2 == 0
```
Which of the following will print `True`?

A) `print(is_even(7))`  
B) `print(is_even(0))`  
C) `print(is_even(-3))`  
D) `print(is_even(15))`  

---

### Question 36
What is returned by `sum_digits(456)`?
```python
def sum_digits(n):
    total = 0
    while n > 0:
        total += n % 10
        n = n // 10
    return total
```

A) `11`  
B) `15`  
C) `456`  
D) `6`  

---

### Question 37
What is the output of this code?
```python
def print_numbers(n):
    if n > 0:
        print(n, end=" ")
        print_numbers(n - 1)

print_numbers(3)
```

A) `1 2 3 `  
B) `3 2 1 `  
C) `3 2 1 0 `  
D) `1 2 3 0 `  

---

### Question 38
What does `gcd(48, 18)` return?
```python
def gcd(a, b):
    if b == 0:
        return a
    return gcd(b, a % b)
```

A) `2`  
B) `3`  
C) `6`  
D) `18`  

---

### Question 39
What is the output?
```python
def compute(x, y):
    if x > y:
        return x - y
    return y - x

print(compute(5, 8) + compute(10, 4))
```

A) `3`  
B) `6`  
C) `9`  
D) `12`  

---

### Question 40
What value is returned by `fib(6)`?
```python
def fib(n):
    if n <= 1:
        return n
    return fib(n - 1) + fib(n - 2)
```

A) `5`  
B) `6`  
C) `8`  
D) `13`  

---

## Free Response Questions

### Question 41
Write a function `find_max` that takes three integer parameters and returns the largest of the three values. **Do not use the built-in max function.**

```python
def find_max(a, b, c):
    # Your code here
    pass
```

**Sample calls:**
- `find_max(5, 12, 8)` returns `12`
- `find_max(-1, -5, -3)` returns `-1`

---

### Question 42
Write a function `is_prime` that takes an integer parameter and returns `True` if the number is prime, `False` otherwise. A prime number is greater than 1 and only divisible by 1 and itself.

```python
def is_prime(n):
    # Your code here
    pass
```

**Sample calls:**
- `is_prime(7)` returns `True`
- `is_prime(12)` returns `False`
- `is_prime(1)` returns `False`

---

### Question 43
Write a function `reverse_digits` that takes a positive integer and returns the integer with its digits reversed.

```python
def reverse_digits(n):
    # Precondition: n > 0
    # Your code here
    pass
```

**Sample calls:**
- `reverse_digits(12345)` returns `54321`
- `reverse_digits(100)` returns `1`

---

### Question 44
Write a function `count_factors` that takes a positive integer and returns the count of its positive factors (divisors).

```python
def count_factors(n):
    # Precondition: n > 0
    # Your code here
    pass
```

**Sample calls:**
- `count_factors(12)` returns `6` (factors: 1, 2, 3, 4, 6, 12)
- `count_factors(7)` returns `2` (factors: 1, 7)

---

### Question 45
Write a function `convert_to_base` that takes two parameters: a positive integer `n` and a base `b` (where 2 ≤ b ≤ 10), and returns a string representing `n` in the specified base.

```python
def convert_to_base(n, b):
    # Precondition: n > 0, 2 <= b <= 10
    # Your code here
    pass
```

**Sample calls:**
- `convert_to_base(10, 2)` returns `"1010"`
- `convert_to_base(255, 8)` returns `"377"`
- `convert_to_base(100, 10)` returns `"100"`

---

---

# Answer Key

## Part A: Strings (Multiple Choice)

| Question | Answer | Explanation |
|----------|--------|-------------|
| 1 | A | `s[3:6]` extracts characters at indices 3, 4, 5 → "put" |
| 2 | C | First 'm' appears at index 7 (0-indexed) |
| 3 | A | `s[:2]` = "AP", `s[3:11]` = "Computer" → "APComputer" |
| 4 | B | `==` compares values (all True), `is` compares identity (may be False) |
| 5 | B | Strings are immutable; concatenation creates new string (not assigned) |
| 6 | C | "Mississippi" has 4 letter 's' |
| 7 | C | `[3:]` returns from index 3 to end → "ucation" |
| 8 | B | `len("Alice")` = 5, `find("i")` = 2, so 5 + 2 = 7 |
| 9 | A | "apple" < "banana" lexicographically (True) |
| 10 | B | Iterates backwards through indices, building "SCPA" |
| 11 | B | Takes characters at indices 0, 2, 4 → "hlo" |
| 12 | B | `find()` returns -1 when substring is not found |
| 13 | A | `s[7:]` = "is fun", then `[:2]` = "is" |
| 14 | A | `find("o")` = 4 (first), `rfind("o")` = 7 (last) |
| 15 | B | Concatenates "11" + "22" + "33" = "112233" |
| 16 | B | "hello world" has 3 l's total |
| 17 | D | `s[1:4]` = "yth", `s[-2:]` = "on" → "ython" |
| 18 | C | `replace("m", "x", 1)` replaces only first 'm' |
| 19 | B | `s[::2]` takes every 2nd character → "ace" |
| 20 | C | `strip()` removes spaces, "hello" has length 5 |

---

## Part A: Strings (Free Response Solutions)

**Q21: Count Vowels**
```python
def count_vowels(s):
    s = s.lower()
    count = 0
    vowels = "aeiou"
    for char in s:
        if char in vowels:
            count += 1
    return count
```

**Q22: Is Palindrome**
```python
def is_palindrome(s):
    left = 0
    right = len(s) - 1
    while left < right:
        if s[left] != s[right]:
            return False
        left += 1
        right -= 1
    return True
```

*Alternative solution:*
```python
def is_palindrome(s):
    return s == s[::-1]
```

**Q23: Remove Character**
```python
def remove_char(s, char):
    result = ""
    for c in s:
        if c != char:
            result += c
    return result
```

**Q24: Replace First**
```python
def replace_first(original, target, replacement):
    index = original.find(target)
    if index == -1:
        return original
    return original[:index] + replacement + original[index + len(target):]
```

**Q25: Scramble**
```python
def scramble(s1, s2):
    result = ""
    for i in range(len(s1)):
        result += s1[i] + s2[i]
    return result
```

---

## Part B: Functions (Multiple Choice)

| Question | Answer | Explanation |
|----------|--------|-------------|
| 26 | B | Integers are immutable; `num` unchanged after function call |
| 27 | A | Both calls return the minimum (3), so 3 + 3 = 6 |
| 28 | C | Factorial: 4! = 4 × 3 × 2 × 1 = 24 |
| 29 | C | Sum of 1+2+3+4+5 = 15 |
| 30 | A | Integers are passed by value; `num` stays 5 |
| 31 | B | `foo(3)` = 6, `foo(2, 3)` = 5, total = 11 |
| 32 | C | Counts digits: 12345 has 5 digits |
| 33 | C | 2^5 = 32 |
| 34 | C | `x` unchanged (10), `y` gets returned value (11) |
| 35 | B | 0 % 2 == 0 is True |
| 36 | B | 4 + 5 + 6 = 15 |
| 37 | B | Prints 3, then recurses with 2, then 1, then stops |
| 38 | C | GCD of 48 and 18 is 6 (Euclidean algorithm) |
| 39 | C | `compute(5,8)` = 3, `compute(10,4)` = 6, total = 9 |
| 40 | C | Fibonacci: 0, 1, 1, 2, 3, 5, 8 → fib(6) = 8 |

---

## Part B: Functions (Free Response Solutions)

**Q41: Find Max**
```python
def find_max(a, b, c):
    maximum = a
    if b > maximum:
        maximum = b
    if c > maximum:
        maximum = c
    return maximum
```

**Q42: Is Prime**
```python
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
```

**Q43: Reverse Digits**
```python
def reverse_digits(n):
    reversed_num = 0
    while n > 0:
        reversed_num = reversed_num * 10 + n % 10
        n = n // 10
    return reversed_num
```

**Q44: Count Factors**
```python
def count_factors(n):
    count = 0
    for i in range(1, n + 1):
        if n % i == 0:
            count += 1
    return count
```

**Q45: Convert to Base**
```python
def convert_to_base(n, b):
    if n == 0:
        return "0"
    result = ""
    while n > 0:
        result = str(n % b) + result
        n = n // b
    return result
```

---

---

# Quick Reference: Python String Methods

| Method | Returns | Example |
|--------|---------|---------|
| `len(s)` | int | `len("hello")` → `5` |
| `s[start:end]` | str | `"hello"[1:4]` → `"ell"` |
| `s[start:]` | str | `"hello"[2:]` → `"llo"` |
| `s[:end]` | str | `"hello"[:3]` → `"hel"` |
| `s[::step]` | str | `"hello"[::2]` → `"hlo"` |
| `s[::-1]` | str | `"hello"[::-1]` → `"olleh"` |
| `s.find(sub)` | int | `"hello".find("l")` → `2` |
| `s.rfind(sub)` | int | `"hello".rfind("l")` → `3` |
| `s.count(sub)` | int | `"hello".count("l")` → `2` |
| `s.lower()` | str | `"Hello".lower()` → `"hello"` |
| `s.upper()` | str | `"Hello".upper()` → `"HELLO"` |
| `s.strip()` | str | `"  hi  ".strip()` → `"hi"` |
| `s.replace(old, new)` | str | `"hello".replace("l", "x")` → `"hexxo"` |
| `s.split(sep)` | list | `"a,b,c".split(",")` → `["a", "b", "c"]` |
| `sep.join(list)` | str | `"-".join(["a", "b"])` → `"a-b"` |
| `s in string` | bool | `"el" in "hello"` → `True` |

---

# Quick Reference: Python Function Concepts

| Concept | Description | Example |
|---------|-------------|---------|
| **Parameters** | Variables in function definition | `def add(a, b):` |
| **Arguments** | Values passed to function | `add(3, 5)` |
| **Return value** | Value sent back by function | `return result` |
| **Default parameters** | Parameters with default values | `def greet(name="World"):` |
| **Scope** | Variables inside function are local | Changes don't affect outside |
| **Recursion** | Function calls itself | Base case + recursive case |
| **Integer division** | `//` operator | `7 // 2` → `3` |
| **Modulo** | `%` operator (remainder) | `7 % 2` → `1` |

---

# Common Patterns

## String Traversal
```python
# Using index
for i in range(len(s)):
    print(s[i])

# Using character directly
for char in s:
    print(char)
```

## Building a String
```python
result = ""
for char in s:
    if some_condition:
        result += char
```

## Digit Processing
```python
while n > 0:
    digit = n % 10      # Get last digit
    n = n // 10         # Remove last digit
```

## Recursion Template
```python
def recursive_function(n):
    # Base case
    if n <= 0:
        return base_value
    # Recursive case
    return some_operation(recursive_function(n - 1))
```
