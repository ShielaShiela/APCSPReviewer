# AP Computer Science Principles
## Big Idea 3: Algorithms and Programming
### Focus: Decision-Making in Programs

---

## Section 1: Warm-Up Questions (Boolean Basics)

**Use this code for Questions 1-3:**
```python
x = 7
if x > 5 and x < 10:
    print("Yes")
else:
    print("No")
```

**Question 1**
What is the output of the code above?

(A) Yes  
(B) No  
(C) True  
(D) 7

---

**Question 2**
If the value of `x` is changed to `5`, what will be the output?

(A) Yes  
(B) No  
(C) True  
(D) Nothing will print

---

**Question 3**
Which of the following values of `x` would cause the program to print "Yes"? Select TWO answers.

(A) 5  
(B) 6  
(C) 10  
(D) 8

---

**Question 4**
What does the expression `x > 5 and x < 10` evaluate to when `x = 7`?

(A) 7  
(B) True  
(C) False  
(D) "Yes"

---

## Section 2: Boolean Expressions

**Question 5**
Which of the following is a Boolean expression?

(A) `x = 5`  
(B) `x + 3`  
(C) `x == 5`  
(D) `print(x)`

---

**Question 6**
A Boolean expression can only evaluate to which of the following?

(A) Any number  
(B) True or False  
(C) Yes or No  
(D) 1, 2, or 3

---

**Question 7**
Consider the expression: `temperature >= 32`

If `temperature = 32`, what does this expression evaluate to?

(A) True  
(B) False  
(C) 32  
(D) Error

---

**Question 8**
Which Boolean expression correctly checks if a variable `age` is exactly equal to 18?

(A) `age = 18`  
(B) `age == 18`  
(C) `age != 18`  
(D) `age >= 18`

---

## Section 3: AND / OR Logic

**Question 9**
For the expression `A and B` to evaluate to True:

(A) Only A must be True  
(B) Only B must be True  
(C) Both A and B must be True  
(D) Either A or B must be True

---

**Question 10**
For the expression `A or B` to evaluate to True:

(A) Both A and B must be True  
(B) At least one of A or B must be True  
(C) Neither A nor B can be True  
(D) A and B must have the same value

---

**Question 11**
Complete this truth table for `A and B`:

| A     | B     | A and B |
|-------|-------|---------|
| True  | True  | ?       |
| True  | False | ?       |
| False | True  | ?       |
| False | False | ?       |

What are the values in order from top to bottom?

(A) True, True, True, True  
(B) True, False, False, False  
(C) True, True, True, False  
(D) False, False, False, True

---

**Question 12**
Complete this truth table for `A or B`:

| A     | B     | A or B |
|-------|-------|--------|
| True  | True  | ?      |
| True  | False | ?      |
| False | True  | ?      |
| False | False | ?      |

What are the values in order from top to bottom?

(A) True, True, True, False  
(B) True, False, False, False  
(C) False, False, False, True  
(D) True, True, True, True

---

**Question 13**
Given: `score = 85` and `attendance = 90`

What does `score >= 80 and attendance >= 85` evaluate to?

(A) True  
(B) False  
(C) 85  
(D) 90

---

**Question 14**
Given: `rain = True` and `cold = False`

What does `rain or cold` evaluate to?

(A) True  
(B) False  
(C) rain  
(D) Error

---

**Question 15**
Given: `hasTicket = False` and `isVIP = False`

What does `hasTicket or isVIP` evaluate to?

(A) True  
(B) False  
(C) hasTicket  
(D) None

---

## Section 4: If/Else Flow

**Question 16**
```python
grade = 75
if grade >= 70:
    print("Pass")
else:
    print("Fail")
```

What is the output?

(A) Pass  
(B) Fail  
(C) 75  
(D) Both Pass and Fail

---

**Question 17**
In an if/else statement, how many branches can execute?

(A) Both branches always execute  
(B) Exactly one branch executes  
(C) Zero branches execute  
(D) It depends on the condition

---

**Question 18**
```python
x = 10
if x > 10:
    print("A")
else:
    print("B")
```

What is the output?

(A) A  
(B) B  
(C) AB  
(D) Nothing

---

**Question 19**
```python
temperature = 100
if temperature > 90:
    print("Hot")
if temperature > 80:
    print("Warm")
```

What is the output?

(A) Hot  
(B) Warm  
(C) Hot followed by Warm  
(D) Nothing

---

**Question 20**
```python
temperature = 100
if temperature > 90:
    print("Hot")
else:
    if temperature > 80:
        print("Warm")
```

What is the output?

(A) Hot  
(B) Warm  
(C) Hot followed by Warm  
(D) Nothing

---

## Section 5: Condition Evaluation & "Which Branch Runs?"

**Question 21**
```python
age = 16
hasPermission = True

if age >= 18 or hasPermission:
    print("Allowed")
else:
    print("Denied")
```

What is the output?

(A) Allowed  
(B) Denied  
(C) True  
(D) Error

---

**Question 22**
```python
points = 50
bonus = False

if points >= 100 and bonus:
    print("Winner")
else:
    print("Keep playing")
```

What is the output?

(A) Winner  
(B) Keep playing  
(C) True  
(D) False

---

**Question 23**
```python
x = 0
if x:
    print("Truthy")
else:
    print("Falsy")
```

What is the output? (Note: In Python, 0 is considered False)

(A) Truthy  
(B) Falsy  
(C) 0  
(D) Error

---

**Question 24**
```python
a = 5
b = 10
c = 15

if a < b and b < c:
    print("Ascending")
else:
    print("Not ascending")
```

What is the output?

(A) Ascending  
(B) Not ascending  
(C) True  
(D) 5 10 15

---

**Question 25**
```python
password = "secret"
attempts = 3

if password == "secret" and attempts > 0:
    print("Access granted")
else:
    print("Access denied")
```

What is the output?

(A) Access granted  
(B) Access denied  
(C) secret  
(D) 3

---

## Section 6: Rewriting Conditions in Plain English

**Question 26**
The condition `age >= 13 and age <= 19` can be described in plain English as:

(A) Age is greater than 13 or less than 19  
(B) Age is a teenager (between 13 and 19, inclusive)  
(C) Age is exactly 13 or exactly 19  
(D) Age is not a teenager

---

**Question 27**
Which code correctly represents: "The user can enter if they are 21 or older, OR if they have a parent with them"?

(A) `if age >= 21 and hasParent:`  
(B) `if age >= 21 or hasParent:`  
(C) `if age > 21 or hasParent:`  
(D) `if age == 21 and hasParent:`

---

**Question 28**
The condition `not (x == 5)` is equivalent to:

(A) `x == 5`  
(B) `x != 5`  
(C) `x > 5`  
(D) `x < 5`

---

## Section 7: Strategy Application

**Question 29**
```python
x = 8
y = 3

if x > 5 and y < 5:
    result = "A"
else:
    result = "B"
```

To determine the value of `result`, which strategy is most effective?

(A) Guess the answer  
(B) Evaluate each condition separately first, then combine with AND  
(C) Only look at the first condition  
(D) Skip to the else branch

Using the correct strategy, what is the value of `result`?

---

**Question 30**
A student is debugging this code and getting unexpected results:

```python
score = 85
if score > 90 or score > 80:
    print("Great job!")
```

The student expected "Great job!" to print only for scores above 90. What is wrong with their condition?

(A) The condition should use `and` instead of `or`  
(B) The condition should use `>=` instead of `>`  
(C) The variable name is wrong  
(D) Nothing is wrong; the code works correctly

---

# Answer Key

| Question | Answer | Explanation |
|----------|--------|-------------|
| 1 | A | 7 > 5 is True, 7 < 10 is True, True AND True = True |
| 2 | B | 5 > 5 is False, False AND anything = False |
| 3 | B, D | Both 6 and 8 satisfy x > 5 AND x < 10 |
| 4 | B | Boolean expressions evaluate to True or False |
| 5 | C | `==` creates a comparison that returns True/False |
| 6 | B | Boolean values are only True or False |
| 7 | A | 32 >= 32 is True (equal counts for >=) |
| 8 | B | `==` checks equality; `=` is assignment |
| 9 | C | AND requires both conditions to be True |
| 10 | B | OR requires at least one condition to be True |
| 11 | B | AND only returns True when both are True |
| 12 | A | OR returns False only when both are False |
| 13 | A | 85 >= 80 is True, 90 >= 85 is True, True AND True = True |
| 14 | A | True OR False = True |
| 15 | B | False OR False = False |
| 16 | A | 75 >= 70 is True, so "Pass" prints |
| 17 | B | In if/else, exactly one branch executes |
| 18 | B | 10 > 10 is False (not strictly greater), so else runs |
| 19 | C | Two separate if statements, both conditions are True |
| 20 | A | With if/else, only one branch runs; 100 > 90 is True |
| 21 | A | 16 >= 18 is False, but hasPermission is True; False OR True = True |
| 22 | B | 50 >= 100 is False; False AND anything = False |
| 23 | B | In Python, 0 is "falsy" and evaluates to False |
| 24 | A | 5 < 10 is True, 10 < 15 is True; True AND True = True |
| 25 | A | Both conditions are True; True AND True = True |
| 26 | B | The condition checks if age is between 13 and 19 inclusive |
| 27 | B | "OR" means either condition grants access |
| 28 | B | NOT equal to 5 is the same as != 5 |
| 29 | A | x > 5 → 8 > 5 → True; y < 5 → 3 < 5 → True; True AND True = True |
| 30 | A | Using OR means either condition triggers; AND would require both |

---

## Quick Reference: Strategy Tips

### Evaluate Conditions FIRST
1. Look at each part of the condition separately
2. Substitute the actual values
3. Determine if each part is True or False
4. Then combine using AND/OR rules

### AND vs OR Memory Trick
- **AND** = BOTH must be True (stricter)
- **OR** = AT LEAST ONE must be True (more flexible)

### Plain English Translations
- `and` → "both conditions must be met"
- `or` → "either condition is enough"
- `>=` → "at least" or "minimum of"
- `<=` → "at most" or "maximum of"
- `==` → "exactly equals"
- `!=` → "is not equal to"
