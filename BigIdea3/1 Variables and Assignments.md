# Variables & Assignment - AP-Style Practice Questions

## Instructions
- Each question focuses on tracing variables, understanding assignment vs reassignment, and avoiding common misconceptions
- Read code line by line carefully
- Remember: variables do NOT auto-update when other variables change
- Time: 15 minutes (approximately 30 seconds per question)

---

## Section 1: Basic Variable Assignment (Questions 1-8)

**Question 1**
```python
x = 5
y = x
x = 10
```
What is the value of `y` after this code executes?

A) 5  
B) 10  
C) 15  
D) Error

---

**Question 2**
```python
a = 3
b = a + 2
a = 7
```
What is the value of `b` after this code executes?

A) 3  
B) 5  
C) 7  
D) 9

---

**Question 3**
```python
price = 100
discount = price * 0.1
price = 200
```
What is the value of `discount` after this code executes?

A) 10.0  
B) 20.0  
C) 100  
D) 200

---

**Question 4**
```python
x = 8
x = x + 2
x = x * 3
```
What is the value of `x` after this code executes?

A) 8  
B) 10  
C) 24  
D) 30

---

**Question 5**
```python
num1 = 15
num2 = num1
num1 = num1 - 5
```
What is the value of `num2` after this code executes?

A) 5  
B) 10  
C) 15  
D) 20

---

**Question 6**
```python
total = 0
total = total + 5
total = total + 3
```
What is the value of `total` after this code executes?

A) 0  
B) 3  
C) 5  
D) 8

---

**Question 7**
```python
score = 50
bonus = score / 10
score = 100
final_score = score + bonus
```
What is the value of `final_score` after this code executes?

A) 55.0  
B) 100  
C) 105.0  
D) 110.0

---

**Question 8**
```python
a = 12
b = a / 2
a = a + 4
c = a - b
```
What is the value of `c` after this code executes?

A) 4.0  
B) 6.0  
C) 10.0  
D) 16.0

---

## Section 2: Multiple Variable Interactions (Questions 9-16)

**Question 9**
```python
x = 4
y = 6
z = x + y
x = 8
```
What is the value of `z` after this code executes?

A) 4  
B) 10  
C) 14  
D) 18

---

**Question 10**
```python
first = 20
second = 30
first = second
second = 40
```
What is the value of `first` after this code executes?

A) 20  
B) 30  
C) 40  
D) 50

---

**Question 11**
```python
p = 7
q = p * 2
p = 5
r = p + q
```
What is the value of `r` after this code executes?

A) 12  
B) 14  
C) 19  
D) 21

---

**Question 12**
```python
width = 10
height = 5
area = width * height
width = 15
```
What is the value of `area` after this code executes?

A) 50  
B) 75  
C) 150  
D) 200

---

**Question 13**
```python
base = 100
tax = base * 0.08
total = base + tax
base = 150
```
What is the value of `total` after this code executes?

A) 108.0  
B) 150  
C) 158.0  
D) 162.0

---

**Question 14**
```python
a = 3
b = 4
c = 5
a = b
b = c
c = a
```
What is the value of `c` after this code executes?

A) 3  
B) 4  
C) 5  
D) 7

---

**Question 15**
```python
x = 10
y = 20
temp = x
x = y
y = temp
result = x + y
```
What is the value of `result` after this code executes?

A) 20  
B) 30  
C) 40  
D) 50

---

**Question 16**
```python
num = 25
double = num * 2
num = num + 10
triple = num * 3
```
What is the value of `double` after this code executes?

A) 35  
B) 50  
C) 70  
D) 105

---

## Section 3: Tracing Complex Sequences (Questions 17-24)

**Question 17**
```python
counter = 0
counter = counter + 1
counter = counter + 1
counter = counter + 1
```
What is the value of `counter` after this code executes?

A) 0  
B) 1  
C) 2  
D) 3

---

**Question 18**
```python
value = 100
value = value / 2
value = value - 10
value = value * 2
```
What is the value of `value` after this code executes?

A) 40.0  
B) 50.0  
C) 80.0  
D) 90.0

---

**Question 19**
```python
start = 5
middle = start + 3
end = middle * 2
start = 10
final = start + middle + end
```
What is the value of `final` after this code executes?

A) 26  
B) 34  
C) 44  
D) 50

---

**Question 20**
```python
x = 2
y = 3
x = x + y
y = x - y
x = x - y
```
What is the value of `x` after this code executes?

A) 2  
B) 3  
C) 5  
D) 8

---

**Question 21**
```python
balance = 1000
withdrawal = 200
balance = balance - withdrawal
deposit = 500
balance = balance + deposit
withdrawal = 100
```
What is the value of `balance` after this code executes?

A) 1000  
B) 1200  
C) 1300  
D) 1400

---

**Question 22**
```python
length = 8
width = length / 2
perimeter = 2 * (length + width)
length = 10
```
What is the value of `perimeter` after this code executes?

A) 24.0  
B) 28.0  
C) 30.0  
D) 40.0

---

**Question 23**
```python
a = 6
b = 9
c = a
a = b
b = c
total = a + b + c
```
What is the value of `total` after this code executes?

A) 15  
B) 18  
C) 21  
D) 24

---

**Question 24**
```python
original = 45
half = original / 2
double = original * 2
original = 60
combined = half + double
```
What is the value of `combined` after this code executes?

A) 90.0  
B) 105.0  
C) 112.5  
D) 120.0

---

## Section 4: Common Misconceptions (Questions 25-30)

**Question 25**
Which statement is TRUE about variable assignment?

A) When you assign `y = x`, both variables always have the same value  
B) When you assign `y = x`, y gets the current value of x at that moment  
C) Variables automatically update when related variables change  
D) Reassigning x will automatically change y if y was assigned from x

---

**Question 26**
```python
temperature = 70
celsius = (temperature - 32) * 5 / 9
temperature = 100
```
Why doesn't `celsius` change when `temperature` is reassigned?

A) There's an error in the code  
B) Variables only update when explicitly reassigned  
C) The formula is incorrect  
D) Celsius depends on Fahrenheit, so it should update

---

**Question 27**
```python
item_price = 50
total_price = item_price * 3
item_price = 60
```
A student thinks `total_price` should now be 180. What is the correct value?

A) 150  
B) 160  
C) 180  
D) 200

---

**Question 28**
What does the statement `x = x + 1` mean?

A) It checks if x equals x + 1  
B) It creates an infinite loop  
C) It takes the current value of x, adds 1, and stores the result back in x  
D) It's a syntax error

---

**Question 29**
```python
principal = 1000
interest = principal * 0.05
principal = 2000
earnings = interest
```
What is the value of `earnings`?

A) 50.0  
B) 100.0  
C) 150.0  
D) 200.0

---

**Question 30**
Which of the following best describes reading code execution?

A) Read all lines at once to understand the program  
B) Focus only on the final assignment statements  
C) Read line by line, top to bottom, updating variables as you go  
D) Variables keep track of all their previous values automatically

---

## Answer Key

1. A) 5 - y gets x's value (5) at assignment; x changing later doesn't affect y
2. B) 5 - b = 3 + 2 = 5; changing a doesn't change b
3. A) 10.0 - discount = 100 * 0.1 = 10.0; price change doesn't affect discount
4. D) 30 - x = 8, then 8+2=10, then 10*3=30
5. C) 15 - num2 gets the value 15 from num1; num1 changing doesn't affect num2
6. D) 8 - total starts at 0, becomes 5, then 8
7. C) 105.0 - bonus = 50/10 = 5.0; final_score = 100 + 5.0 = 105.0
8. C) 10.0 - b=6.0, a becomes 16, c = 16-6.0 = 10.0
9. B) 10 - z = 4 + 6 = 10; x changing later doesn't affect z
10. B) 30 - first gets second's value (30); second changing later doesn't affect first
11. C) 19 - q = 7*2 = 14, p becomes 5, r = 5+14 = 19
12. A) 50 - area = 10*5 = 50; width changing doesn't affect area
13. A) 108.0 - tax = 8.0, total = 100+8.0 = 108.0; base change doesn't affect total
14. B) 4 - trace: a=4, b=5, c=4
15. B) 30 - swap makes x=20, y=10; result = 20+10 = 30
16. B) 50 - double = 25*2 = 50; num changing doesn't affect double
17. D) 3 - counter increments three times: 0→1→2→3
18. C) 80.0 - 100/2=50, 50-10=40, 40*2=80
19. B) 34 - middle=8, end=16, start becomes 10, final=10+8+16=34
20. B) 3 - this swaps x and y; x ends with original y value (3)
21. C) 1300 - balance: 1000→800→1300 (withdrawal reassignment doesn't affect balance)
22. A) 24.0 - width=4.0, perimeter=2*(8+4)=24.0; length change doesn't affect perimeter
23. C) 21 - a=9, b=6, c=6; total=9+6+6=21
24. C) 112.5 - half=22.5, double=90, combined=22.5+90=112.5
25. B) - This is the correct understanding of assignment
26. B) - Variables don't auto-update; they must be explicitly reassigned
27. A) 150 - total_price was calculated when item_price was 50
28. C) - This describes reassignment/increment correctly
29. A) 50.0 - interest = 1000*0.05 = 50.0; earnings gets this value
30. C) - Correct way to trace code execution

## Key Concepts Reinforced

✓ **Variables store values** - they hold a specific value at any given time
✓ **Assignment captures current value** - when you write `y = x`, y gets x's value *at that moment*
✓ **No auto-updating** - changing x later does NOT change y
✓ **Reassignment replaces** - `x = 10` replaces whatever x held before
✓ **Read line by line** - trace code execution sequentially
✓ **Right side evaluates first** - in `x = x + 1`, right side uses old x value to create new x value
