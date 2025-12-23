# Big Idea 3 Practice Questions – Set A
## Lists, Iteration, and List Traversal

---

### Section 1: Lists & Indexing (Questions 1–5)

**Question 1**
Consider the following code segment:
```
animals = ["cat", "dog", "bird", "fish"]
print(animals[2])
```
What is displayed as a result of executing this code?

(A) cat  
(B) dog  
(C) bird  
(D) fish

---

**Question 2**
Consider the following code segment:
```
scores = [85, 92, 78, 90, 88]
scores[1] = 95
print(scores)
```
What is displayed as a result of executing this code?

(A) [95, 92, 78, 90, 88]  
(B) [85, 95, 78, 90, 88]  
(C) [85, 92, 95, 90, 88]  
(D) An error occurs

---

**Question 3**
Consider the following code segment:
```
colors = ["red", "green", "blue"]
x = len(colors)
print(colors[x])
```
What is displayed as a result of executing this code?

(A) red  
(B) blue  
(C) 3  
(D) An error occurs because the index is out of range

---

**Question 4**
A list called `temps` contains the following values: [72, 68, 75, 80, 77]

Which of the following expressions will correctly access the LAST element in the list?

(A) temps[5]  
(B) temps[4]  
(C) temps[-1]  
(D) Both B and C

---

**Question 5**
Consider the following code segment:
```
data = [10, 20, 30, 40]
data[0] = data[2]
print(data)
```
What is displayed as a result of executing this code?

(A) [30, 20, 30, 40]  
(B) [10, 20, 10, 40]  
(C) [30, 20, 10, 40]  
(D) An error occurs

---

### Section 2: Iteration – for & while Loops (Questions 6–10)

**Question 6**
Consider the following code segment:
```
count = 0
for i in range(5):
    count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 4  
(B) 5  
(C) 6  
(D) 10

---

**Question 7**
Consider the following code segment:
```
total = 0
for i in range(3):
    total = total + i
print(total)
```
What is displayed as a result of executing this code?

(A) 3  
(B) 6  
(C) 0  
(D) 1 + 2 + 3

---

**Question 8**
Consider the following code segment:
```
x = 10
while x > 0:
    x = x - 3
print(x)
```
What is displayed as a result of executing this code?

(A) 0  
(B) 1  
(C) -2  
(D) 3

---

**Question 9**
Which of the following code segments will result in an infinite loop?

(A)
```
n = 5
while n > 0:
    n = n - 1
```

(B)
```
n = 5
while n > 0:
    n = n + 1
```

(C)
```
for i in range(10):
    print(i)
```

(D)
```
n = 10
while n != 0:
    n = n - 2
```

---

**Question 10**
Consider the following code segment:
```
result = 1
for i in range(1, 4):
    result = result * i
print(result)
```
What is displayed as a result of executing this code?

(A) 4  
(B) 6  
(C) 10  
(D) 24

---

### Section 3: List Traversal with Loops (Questions 11–15)

**Question 11**
Consider the following code segment:
```
numbers = [5, 10, 15, 20]
sum = 0
for num in numbers:
    sum = sum + num
print(sum)
```
What is displayed as a result of executing this code?

(A) 20  
(B) 50  
(C) 4  
(D) 15

---

**Question 12**
Consider the following code segment:
```
grades = [85, 90, 78, 92, 88]
count = 0
for g in grades:
    if g >= 90:
        count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 1  
(B) 2  
(C) 3  
(D) 5

---

**Question 13**
Consider the following code segment:
```
words = ["apple", "banana", "cherry"]
result = ""
for w in words:
    result = result + w[0]
print(result)
```
What is displayed as a result of executing this code?

(A) apple  
(B) abc  
(C) AppleBananaCherry  
(D) a b c

---

**Question 14**
A programmer wants to find the largest value in a list. Consider the following code:
```
values = [34, 67, 23, 89, 45]
largest = values[0]
for v in values:
    if v > largest:
        largest = v
print(largest)
```
What is displayed as a result of executing this code?

(A) 34  
(B) 45  
(C) 89  
(D) 67

---

**Question 15**
Consider the following code segment:
```
nums = [2, 4, 6, 8]
total = 0
for i in range(len(nums)):
    total = total + nums[i]
print(total)
```
What is displayed as a result of executing this code?

(A) 4  
(B) 8  
(C) 20  
(D) An error occurs

---

---

## Answer Key – Set A

| Question | Answer | Explanation |
|----------|--------|-------------|
| 1 | C | Index 2 refers to the third element, which is "bird" |
| 2 | B | Index 1 is modified from 92 to 95 |
| 3 | D | len(colors) returns 3, but valid indices are 0, 1, 2 |
| 4 | D | Both temps[4] and temps[-1] access the last element |
| 5 | A | data[2] is 30, which replaces data[0] |
| 6 | B | The loop runs 5 times (i = 0, 1, 2, 3, 4), adding 1 each time |
| 7 | A | 0 + 1 + 2 = 3 (range(3) gives 0, 1, 2) |
| 8 | C | x goes: 10 → 7 → 4 → 1 → -2, then loop ends |
| 9 | B | n starts at 5 and increases, so n > 0 is always true |
| 10 | B | 1 × 1 × 2 × 3 = 6 (range(1,4) gives 1, 2, 3) |
| 11 | B | 5 + 10 + 15 + 20 = 50 |
| 12 | B | Two grades (90 and 92) are greater than or equal to 90 |



# Big Idea 3 Practice Questions – Set B
## Lists, Iteration, and List Traversal

---

### Section 1: Lists & Indexing (Questions 1–5)

**Question 1**
Consider the following code segment:
```
fruits = ["apple", "banana", "cherry", "date"]
print(fruits[1])
```
What is displayed as a result of executing this code?

(A) apple  
(B) banana  
(C) cherry  
(D) 1

---

**Question 2**
Consider the following code segment:
```
nums = [5, 10, 15, 20, 25]
nums[3] = nums[0] + nums[1]
print(nums)
```
What is displayed as a result of executing this code?

(A) [5, 10, 15, 15, 25]  
(B) [5, 10, 15, 5, 25]  
(C) [15, 10, 15, 20, 25]  
(D) [5, 10, 15, 15, 25]

---

**Question 3**
Consider the following code segment:
```
letters = ["a", "b", "c", "d"]
print(len(letters))
print(letters[len(letters) - 1])
```
What is displayed as a result of executing this code?

(A) 4 and d  
(B) 4 and c  
(C) 3 and d  
(D) An error occurs

---

**Question 4**
Consider the following code segment:
```
items = [100, 200, 300]
items[4] = 400
print(items)
```
What is displayed as a result of executing this code?

(A) [100, 200, 300, 400]  
(B) [100, 200, 300, 0, 400]  
(C) [100, 200, 300, 400, 400]  
(D) An error occurs because the index is out of range

---

**Question 5**
A list named `prices` contains [25, 30, 15, 40, 20]. A programmer wants to swap the first and last elements. Which code segment correctly performs this swap?

(A)
```
prices[0] = prices[4]
prices[4] = prices[0]
```

(B)
```
temp = prices[0]
prices[0] = prices[4]
prices[4] = temp
```

(C)
```
prices[4] = prices[0]
prices[0] = prices[4]
```

(D)
```
prices[0] = 20
prices[4] = 25
```

---

### Section 2: Iteration – for & while Loops (Questions 6–10)

**Question 6**
Consider the following code segment:
```
sum = 0
for i in range(1, 6):
    sum = sum + i
print(sum)
```
What is displayed as a result of executing this code?

(A) 10  
(B) 15  
(C) 21  
(D) 6

---

**Question 7**
Consider the following code segment:
```
x = 1
while x < 20:
    x = x * 2
print(x)
```
What is displayed as a result of executing this code?

(A) 16  
(B) 20  
(C) 32  
(D) 64

---

**Question 8**
How many times does the following loop execute?
```
for i in range(2, 10, 2):
    print(i)
```

(A) 3 times  
(B) 4 times  
(C) 5 times  
(D) 8 times

---

**Question 9**
Consider the following code segment:
```
count = 0
n = 100
while n > 1:
    n = n // 2
    count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 5  
(B) 6  
(C) 7  
(D) 50

---

**Question 10**
Which of the following correctly describes the difference between a for loop and a while loop?

(A) A for loop can only iterate through lists, while a while loop cannot  
(B) A for loop runs a predetermined number of times, while a while loop runs until a condition becomes false  
(C) A while loop is faster than a for loop  
(D) A for loop always runs at least once, while a while loop may not run at all

---

### Section 3: List Traversal with Loops (Questions 11–15)

**Question 11**
Consider the following code segment:
```
temps = [72, 65, 80, 78, 85]
count = 0
for t in temps:
    if t > 75:
        count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 2  
(B) 3  
(C) 4  
(D) 75

---

**Question 12**
Consider the following code segment:
```
numbers = [3, 7, 2, 9, 4]
smallest = numbers[0]
for n in numbers:
    if n < smallest:
        smallest = n
print(smallest)
```
What is displayed as a result of executing this code?

(A) 3  
(B) 2  
(C) 9  
(D) 4

---

**Question 13**
Consider the following code segment:
```
scores = [88, 92, 75, 100, 85]
total = 0
for s in scores:
    total = total + s
average = total / len(scores)
print(average)
```
What is displayed as a result of executing this code?

(A) 440  
(B) 88  
(C) 88.0  
(D) 5

---

**Question 14**
Consider the following code segment:
```
data = [1, 2, 3, 4, 5]
result = []
for d in data:
    result.append(d * 2)
print(result)
```
What is displayed as a result of executing this code?

(A) [1, 2, 3, 4, 5]  
(B) [2, 4, 6, 8, 10]  
(C) 30  
(D) [2, 2, 2, 2, 2]

---

**Question 15**
A programmer wants to count how many negative numbers are in a list. The list is:
`values = [5, -3, 8, -1, 0, -7, 2]`

Which code segment correctly counts the negative numbers?

(A)
```
count = 0
for v in values:
    if v < 0:
        count = count + 1
```

(B)
```
count = 0
for v in values:
    if v > 0:
        count = count + 1
```

(C)
```
count = 0
for v in values:
    count = count + 1
    if v < 0:
        count = count
```

(D)
```
count = 0
for i in range(len(values)):
    if i < 0:
        count = count + 1
```

---

---

## Answer Key – Set B

| Question | Answer | Explanation |
|----------|--------|-------------|
| 1 | B | Index 1 refers to the second element, "banana" |
| 2 | A | nums[0] + nums[1] = 5 + 10 = 15, which replaces index 3 |
| 3 | A | len returns 4; index 3 (len-1) is "d" |
| 4 | D | Cannot assign to index 4 when list only has indices 0-2 |
| 5 | B | A temporary variable is needed to preserve the original value during swap |
| 6 | B | range(1,6) gives 1,2,3,4,5; sum = 1+2+3+4+5 = 15 |
| 7 | C | x doubles: 1→2→4→8→16→32; stops when x ≥ 20, so prints 32 |
| 8 | B | range(2,10,2) gives 2,4,6,8 — four values |
| 9 | B | n: 100→50→25→12→6→3→1; count increments 6 times |
| 10 | B | for loops iterate a known number of times; while loops depend on a condition |
| 11 | B | Three temperatures (80, 78, 85) are greater than 75 |
| 12 | B | 2 is the smallest value in the list |
| 13 | C | (88+92+75+100+85)/5 = 440/5 = 88.0 |
| 14 | B | Each element is doubled: [2, 4, 6, 8, 10] |
| 15 | A | Correctly counts elements less than 0 (there are 3: -3, -1, -7) |
| 13 | B | First character of each word: "a" + "b" + "c" = "abc" |
| 14 | C | 89 is the largest value in the list |
| 15 | C | 2 + 4 + 6 + 8 = 20 |


# Big Idea 3 Practice Questions – Set C (Challenge)
## Lists, Iteration, and List Traversal

---

### Section 1: Lists & Indexing (Questions 1–5)

**Question 1**
Consider the following code segment:
```
matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
result = matrix[1][2] + matrix[2][0]
print(result)
```
What is displayed as a result of executing this code?

(A) 9  
(B) 11  
(C) 13  
(D) 15

---

**Question 2**
Consider the following code segment:
```
data = [10, 20, 30, 40, 50]
data[2] = data[len(data) - 3]
data[0] = data[2] + data[4]
print(data)
```
What is displayed as a result of executing this code?

(A) [80, 20, 30, 40, 50]  
(B) [60, 20, 30, 40, 50]  
(C) [80, 20, 20, 40, 50]  
(D) [60, 20, 20, 40, 50]

---

**Question 3**
Consider the following code segment:
```
words = ["cat", "dog", "bird", "fish", "snake"]
x = len(words) // 2
temp = words[x]
words[x] = words[x - 1]
words[x - 1] = temp
print(words)
```
What is displayed as a result of executing this code?

(A) ["cat", "bird", "dog", "fish", "snake"]  
(B) ["cat", "dog", "fish", "bird", "snake"]  
(C) ["dog", "cat", "bird", "fish", "snake"]  
(D) ["cat", "dog", "bird", "snake", "fish"]

---

**Question 4**
Consider the following code segment:
```
nums = [5, 10, 15, 20]
nums.append(nums[0] + nums[-1])
nums[1] = nums[-1]
print(nums)
```
What is displayed as a result of executing this code?

(A) [5, 25, 15, 20, 25]  
(B) [5, 10, 15, 20, 25]  
(C) [5, 25, 15, 20, 30]  
(D) [5, 20, 15, 20, 25]

---

**Question 5**
A list `grades` contains student scores. The following code is intended to replace any score below 60 with 60:
```
grades = [55, 72, 48, 90, 35, 88]
for i in range(len(grades)):
    <MISSING CODE>
```
Which of the following should replace `<MISSING CODE>` to make the program work as intended?

(A)
```
if grades[i] < 60:
    grades[i] = 60
```

(B)
```
if i < 60:
    grades[i] = 60
```

(C)
```
if grades[i] < 60:
    i = 60
```

(D)
```
if grades < 60:
    grades[i] = 60
```

---

### Section 2: Iteration – for & while Loops (Questions 6–10)

**Question 6**
Consider the following code segment:
```
x = 2
for i in range(4):
    x = x * x
print(x)
```
What is displayed as a result of executing this code?

(A) 16  
(B) 256  
(C) 65536  
(D) 4294967296

---

**Question 7**
Consider the following code segment:
```
a = 5
b = 3
count = 0
while a != b:
    if a > b:
        a = a - b
    else:
        b = b - a
    count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 1  
(B) 2  
(C) 3  
(D) 4

---

**Question 8**
Consider the following code segment:
```
total = 0
for i in range(1, 5):
    for j in range(i):
        total = total + 1
print(total)
```
What is displayed as a result of executing this code?

(A) 6  
(B) 10  
(C) 15  
(D) 20

---

**Question 9**
Consider the following code segment:
```
n = 1234
sum_digits = 0
while n > 0:
    sum_digits = sum_digits + (n % 10)
    n = n // 10
print(sum_digits)
```
What is displayed as a result of executing this code?

(A) 4  
(B) 10  
(C) 1234  
(D) 1

---

**Question 10**
Consider the following code segment:
```
result = 0
for i in range(3):
    for j in range(3):
        if i == j:
            result = result + 1
        elif i < j:
            result = result + 2
print(result)
```
What is displayed as a result of executing this code?

(A) 6  
(B) 9  
(C) 3  
(D) 12

---

### Section 3: List Traversal with Loops (Questions 11–15)

**Question 11**
Consider the following code segment:
```
nums = [4, 7, 2, 9, 1, 5]
result = nums[0]
for i in range(1, len(nums)):
    if nums[i] > result:
        result = nums[i]
    elif nums[i] < nums[i-1]:
        result = result + nums[i]
print(result)
```
What is displayed as a result of executing this code?

(A) 9  
(B) 12  
(C) 15  
(D) 21

---

**Question 12**
Consider the following code segment:
```
data = [3, 1, 4, 1, 5, 9, 2, 6]
count = 0
for i in range(len(data) - 1):
    if data[i] < data[i + 1]:
        count = count + 1
print(count)
```
What is displayed as a result of executing this code?

(A) 4  
(B) 5  
(C) 6  
(D) 7

---

**Question 13**
Consider the following code segment:
```
values = [10, 20, 30, 40, 50]
total = 0
for i in range(len(values)):
    if i % 2 == 0:
        total = total + values[i]
    else:
        total = total - values[i]
print(total)
```
What is displayed as a result of executing this code?

(A) 30  
(B) 150  
(C) 10  
(D) -30

---

**Question 14**
Consider the following code segment intended to remove all occurrences of 0 from a list:
```
nums = [1, 0, 2, 0, 0, 3, 4, 0]
result = []
for n in nums:
    if n != 0:
        result.append(n)
print(result)
```
What is displayed as a result of executing this code?

(A) [1, 2, 3, 4]  
(B) [0, 0, 0, 0]  
(C) [1, 0, 2, 0, 0, 3, 4, 0]  
(D) []

---

**Question 15**
Consider the following code segment:
```
words = ["apple", "banana", "cherry", "date"]
longest = ""
for w in words:
    if len(w) > len(longest):
        longest = w
    elif len(w) == len(longest):
        longest = longest + w[0]
print(longest)
```
What is displayed as a result of executing this code?

(A) banana  
(B) cherry  
(C) bananac  
(D) cherrydate

---

### Section 4: Mixed Challenge Problems (Questions 16–20)

**Question 16**
Consider the following code segment:
```
def mystery(lst):
    result = 0
    for i in range(len(lst)):
        for j in range(i + 1, len(lst)):
            if lst[i] == lst[j]:
                result = result + 1
    return result

print(mystery([1, 2, 1, 3, 1, 2]))
```
What is displayed as a result of executing this code?

(A) 2  
(B) 3  
(C) 4  
(D) 6

---

**Question 17**
Consider the following code segment:
```
nums = [5, 3, 8, 1, 9, 2]
for i in range(len(nums) - 1):
    if nums[i] > nums[i + 1]:
        temp = nums[i]
        nums[i] = nums[i + 1]
        nums[i + 1] = temp
print(nums)
```
What is displayed as a result of executing this code?

(A) [1, 2, 3, 5, 8, 9]  
(B) [3, 5, 1, 8, 2, 9]  
(C) [5, 3, 8, 1, 9, 2]  
(D) [9, 8, 5, 3, 2, 1]

---

**Question 18**
Consider the following code segment:
```
data = [2, 4, 6, 8, 10]
left = 0
right = len(data) - 1
while left < right:
    temp = data[left]
    data[left] = data[right]
    data[right] = temp
    left = left + 1
    right = right - 1
print(data)
```
What is displayed as a result of executing this code?

(A) [2, 4, 6, 8, 10]  
(B) [10, 8, 6, 4, 2]  
(C) [10, 4, 6, 8, 2]  
(D) [2, 8, 6, 4, 10]

---

**Question 19**
A programmer writes the following code to find the second largest value in a list:
```
nums = [15, 42, 8, 42, 23, 16]
largest = nums[0]
second = nums[0]
for n in nums:
    if n > largest:
        second = largest
        largest = n
    elif n > second and n != largest:
        second = n
print(second)
```
What is displayed as a result of executing this code?

(A) 42  
(B) 23  
(C) 16  
(D) 15

---

**Question 20**
Consider the following code segment:
```
grid = [[1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]]
total = 0
for row in range(3):
    for col in range(3):
        if row == col or row + col == 2:
            total = total + grid[row][col]
print(total)
```
What is displayed as a result of executing this code?

(A) 15  
(B) 25  
(C) 30  
(D) 45

---

---

## Answer Key – Set C (Challenge)

| Question | Answer | Explanation |
|----------|--------|-------------|
| 1 | C | matrix[1][2] = 6, matrix[2][0] = 7; 6 + 7 = 13 |
| 2 | A | len(data)-3 = 2, so data[2] stays 30; data[0] = 30 + 50 = 80 |
| 3 | A | x = 2, swaps indices 1 and 2: "dog" and "bird" swap positions |
| 4 | A | append adds 5+20=25, then nums[1] becomes nums[-1] which is 25 |
| 5 | A | Must check if the value at index i is less than 60, then modify that element |
| 6 | C | x: 2→4→16→256→65536 (squared 4 times) |
| 7 | C | Euclidean algorithm: (5,3)→(2,3)→(2,1)→(1,1); 3 iterations |
| 8 | B | Inner loop runs: 1+2+3+4 = 10 times total |
| 9 | B | Extracts digits: 4+3+2+1 = 10 |
| 10 | B | Diagonal (i==j): 3 points; upper triangle (i<j): 3 pairs × 2 = 6; total = 9 |
| 11 | C | result: 4→7→9→(9+1=10)→(10+5=15); adds when element < previous |
| 12 | B | Counts increasing pairs: (3<1)✗,(1<4)✓,(4<1)✗,(1<5)✓,(5<9)✓,(9<2)✗,(2<6)✓ = 5 |
| 13 | A | Even indices: 10+30+50=90; Odd indices: -20-40=-60; 90-60=30 |
| 14 | A | Correctly builds new list with only non-zero elements |
| 15 | C | "banana" is longest (6), "cherry" ties (6), so appends 'c' → "bananac" |
| 16 | C | Counts duplicate pairs: (1,1) appears 3 times = 3 pairs; (2,2) = 1 pair; total = 4 |
| 17 | B | One pass of bubble sort: swaps adjacent if out of order |
| 18 | B | List reversal algorithm using two pointers |
| 19 | B | Finds second largest correctly handling duplicates; 23 is second to 42 |
| 20 | B | Main diagonal: 1+5+9=15; Anti-diagonal: 3+5+7=15; 5 counted once: 15+15-5=25 |
