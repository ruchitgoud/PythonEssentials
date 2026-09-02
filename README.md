<div align="center">

# 🚀 *Master Python Basics in Just One Week*

![Python](https://img.shields.io/badge/Python-Basics-3776AB?style=flat-square&logo=python)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=flat-square)
![Days](https://img.shields.io/badge/Duration-6%20Days-brightgreen?style=flat-square)

This repository is your complete companion for understanding Python fundamentals, from basic syntax to control flow. By the end of Day 7, you'll have hands-on experience with the essential Python concepts that form the foundation for any software development journey.

---

</div>

## 📚 Quick Navigation

| Day | Topic | Difficulty | File |
|-----|-------|-----------|------|
| **Day 1** | [Print, Variables, Data Types & Conditionals](#day-1-print-variables-data-types--conditionals) | 🟢 Easy | `day1.ipynb` |
| **Day 2** | [Loops & Iterations, Lists & Tuples, Dictionary](#day-2-loops--iterations-lists--tuples-dictionary) | 🟡 Medium | `day2.ipynb` |
| **Day 3** | [Sets, Functions & Scope, Recursion](#day-3-sets-functions--scope-recursion) | 🟡 Medium | `day3.ipynb` |
| **Day 4** | [Recursion & BackTracking, Exception Handling](#day-4-recursion--backtracking) | 🟡 Medium | `day4.ipynb` |
| **Day 5** | [Exception Handling, HOF (Map, Filter, Reduce), Class & Objects](#day-5-functions--scope) | 🟡 Medium | `day5.ipynb` |
| **Day 6** | [OOPS, lambda Function](#day-6-file-handling--exceptions) | 🔴 Hard | `day6.ipynb` |

---

## 🎯 Course Overview

### Learning Objectives

By the end of this 7-day intensive, you will be able to:

✅ **Master Python Syntax**: Print, variables, comments, and basic operations  
✅ **Understand Data Types**: Strings, numbers, booleans, and their operations  
✅ **Control Program Flow**: Use if-elif-else for decision making  
✅ **Work with Collections**: Lists, tuples, dictionaries, and sets  
✅ **Write Reusable Code**: Functions with parameters and return values  
✅ **Handle Errors Gracefully**: Try-except blocks and file operations  
✅ **Build Real Projects**: Create functional programs from scratch  
✅ **Think Like a Programmer**: Problem-solving and debugging skills  

### Requirements

- ✨ A computer with Python installed (3.8+)
- ✨ Text editor or IDE (VS Code, PyCharm, or Jupyter)

---

# 📚 Day-by-Day Learning Modules

## Day 1: Print, Variables, Data Types & Conditionals

**Difficulty**: 🟢 **Easy** | **File**: `day1.ipynb`

### 🎯 What You'll Learn
- Master the **`print()` function** and output formatting
- Create and use **variables** for storing data
- Understand **data types**: strings, integers, floats, booleans
- Perform **basic operations** and type conversions
- Make decisions using **if-elif-else statements**
- Use **comparison and logical operators**
- Take **user input** with `input()` function
- Work with **strings** and their methods

### 📚 Concepts Explained

#### The `print()` Function

The **`print()` function** displays output to the screen. It's your first friend in Python!

```python
print("Hello, World!")                    # Basic string
print(42)                                 # Numbers
print("Name:", "Ruchit", "Age:", 20)     # Multiple items (separated by comma)
print("A", "B", "C", sep=" || ")         # Custom separator
print("Line 1", "Line 2", sep="\n")      # Newline separator
```

**Key Features:**
- 🔤 Prints text, numbers, and expressions
- ➕ Separates multiple items with space (default)
- 🎨 Can customize separator with `sep=`
- ⏎ Adds newline by default (can change with `end=`)

---

#### Variables & Data Types

A **variable** is a container that stores data. Python figures out the data type automatically!

**The Big 4 Data Types:**

```python
# 1. STRING - Text, enclosed in quotes
name = "Ruchit"
message = 'Python is fun'
print(type(name))  # <class 'str'>

# 2. INTEGER - Whole numbers
age = 20
marks = 99
count = -5
print(type(age))  # <class 'int'>

# 3. FLOAT - Decimal numbers
height = 5.9
temperature = 98.6
print(type(height))  # <class 'float'>

# 4. BOOLEAN - True or False
is_student = True
is_married = False
print(type(is_student))  # <class 'bool'>
```

**Naming Rules:**
✅ Can contain letters, numbers, underscores  
✅ Must start with letter or underscore  
❌ Cannot start with number  
❌ Cannot use Python keywords (if, for, while, etc.)

```python
# Good names
student_name = "Ruchit"
_age = 20
scores2024 = 95

# Bad names (will cause error)
# 2name = "Ruchit"  # Starts with number
# student-name = "Ruchit"  # Contains hyphen
# if = 5  # Python keyword
```

---

#### Operators & Operations

**Arithmetic Operators:**

```python
a = 10
b = 3

print(a + b)      # 13 (Addition)
print(a - b)      # 7 (Subtraction)
print(a * b)      # 30 (Multiplication)
print(a / b)      # 3.333... (Division - always returns float)
print(a // b)     # 3 (Floor Division - returns integer)
print(a % b)      # 1 (Modulo - remainder)
print(a ** b)     # 1000 (Exponentiation - power)
```

**Comparison Operators:**

```python
a = 10
b = 5

print(a == b)     # False (Equal to)
print(a != b)     # True (Not equal to)
print(a > b)      # True (Greater than)
print(a < b)      # False (Less than)
print(a >= b)     # True (Greater than or equal)
print(a <= b)     # False (Less than or equal)
```

**Logical Operators:**

```python
a = True
b = False

print(a and b)    # False (Both must be true)
print(a or b)     # True (At least one must be true)
print(not a)      # False (Negates the value)
```

**Membership Operator:**

```python
arr = [3, 5, 8, 9, 7]
print(8 in arr)    # True (8 exists in list)
print(10 in arr)   # False (10 doesn't exist)
```

---

#### Type Conversion

Python allows converting between data types:

```python
# String to Integer
age_str = "25"
age_int = int(age_str)
print(age_int + 5)  # 30 (now it's a number)

# Integer to String
num = 42
num_str = str(num)
print("Answer: " + num_str)  # "Answer: 42"

# String to Float
price_str = "19.99"
price_float = float(price_str)

# Integer to Float
count = 10
count_float = float(count)  # 10.0
```

---

#### User Input

Get data from users with the **`input()` function**:

```python
name = input("Enter your name: ")
print(f"Hello, {name}!")

# input() ALWAYS returns a STRING
age_str = input("Enter your age: ")
age = int(age_str)  # Convert to integer
print(f"Age: {age}")

# Better: Convert immediately
marks = int(input("Enter marks: "))
price = float(input("Enter price: "))
```

---

#### Conditional Statements

Make decisions in your program with **if-elif-else**:

**Basic If-Else:**
```python
age = 18

if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")
```

**Multiple Conditions (If-Elif-Else):**
```python
traffic_light = input("Enter color: ").lower()

if traffic_light == "red":
    print("STOP")
elif traffic_light == "green":
    print("GO")
elif traffic_light == "yellow":
    print("Ready to GO")
else:
    print("Invalid color")
```

**Nested Conditions:**
```python
age = 25

if age >= 18:
    if age >= 60:
        print("Senior Citizen")
    else:
        print("Adult")
else:
    print("Minor")
```

**Combining Conditions:**
```python
marks = 85

if marks >= 90 and marks <= 100:
    grade = "A"
elif marks >= 80 and marks < 90:
    grade = "B"
elif marks >= 70 and marks < 80:
    grade = "C"
else:
    grade = "F"

print(f"Grade: {grade}")
```

---

#### String Methods

Strings have built-in functions you can use:

```python
text = "  Hello World Python  "

print(text.lower())           # "  hello world python  "
print(text.upper())           # "  HELLO WORLD PYTHON  "
print(text.strip())           # "Hello World Python" (removes spaces)
print(text.replace("World", "Universe"))  # "  Hello Universe Python  "
print(text.split(" "))        # ['', '', 'Hello', 'World', 'Python', '', '']
print(text.startswith("Hello"))           # False (has spaces before)
print(text.strip().startswith("Hello"))   # True (after removing spaces)
print(text.count("l"))        # 3 (number of 'l' characters)
print(text.find("World"))     # 8 (position of 'World')
print(len(text))              # 24 (length of string)
print(text.capitalize())      # "  hello world python  " (only first letter)
print(text.swapcase())        # "  hELLO wORLD pYTHON  "
```

---


### 💻 Key Code Snippets from Day 1

#### Basic Output
```python
print("My name is Ruchit Goud", "SAME LINE", sep=" || ")
# Output: My name is Ruchit Goud || SAME LINE

print("Today is Day 1 of Python")
# Output: Today is Day 1 of Python
```

#### Variables & Types
```python
name = "Ruchit"
n = None
arr = [3, 5, 8, 9, 7]

print(8 in arr)      # True
print(type(name))    # <class 'str'>
print(type(arr))     # <class 'list'>
```

#### Arithmetic
```python
a = 5
a = a + 1
# OR
a += 1
print(a)  # 6
```

#### Logical Operations
```python
print(2 == 2 and 4 == 4 and 3 == 4)      # False (last condition fails)
print(2 == 2 or 4 == 4 and 3 == 4)       # True (first two are true)
print(not (2 == 2 or 4 == 4) and 3 == 4) # False
```

#### Type Conversion
```python
a = 2
b = "4"
c = int(b)
print(a + c)  # 6 (now both are integers)
```

#### User Input
```python
name = input("Enter your name: ")
marks = int(input("Enter your marks: "))

print(f"Name = {name}")
print(f"Marks = {marks}")
```

#### String Operations
```python
original = "madam"
reversed_str = original[::-1]

print(f"Is palindrome? {original == reversed_str}")  # True
```

#### Conditional Statements
```python
password = "ruchitgoud1"

if len(password) >= 8:
    if password.isupper() != password.islower():
        print("Strong Password")
    else:
        print("Weak Password")
else:
    print("Weak Password")
```

#### Check Even or Odd
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(f"{num} is EVEN")
else:
    print(f"{num} is ODD")
```

#### Grade Assignment
```python
marks = int(input("Enter marks: "))

if marks >= 90:
    grade = "A"
elif marks >= 80:
    grade = "B"
elif marks >= 70:
    grade = "C"
else:
    grade = "F"

print(f"Grade: {grade}")
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Type |
|-----------|---------|--------|------|
| **Addition** | `5 + 3` | `8` | int |
| **Subtraction** | `5 - 3` | `2` | int |
| **Multiplication** | `5 * 3` | `15` | int |
| **Division** | `5 / 2` | `2.5` | float |
| **Floor Division** | `5 // 2` | `2` | int |
| **Modulo (Remainder)** | `5 % 2` | `1` | int |
| **Power** | `2 ** 3` | `8` | int |
| **String Repeat** | `"Hi" * 3` | `"HiHiHi"` | str |
| **String Join** | `"Hi" + "!"` | `"Hi!"` | str |

---

### 🧪 Practice Problems (Day 1)

**🟢 Easy**
1. Take input of two numbers and print their sum
2. Take input of a side and print the area of square
3. Calculate average of two floating-point numbers
4. Check which number is greater using comparison
5. Convert Celsius to Fahrenheit

**🟡 Medium**

6. Take a password and check if it's strong (length > 8 and mixed case)
7. Check if a number is palindrome
8. Grade assignment based on marks (A: 90+, B: 80+, C: 70+, F: <70)
9. Traffic light simulator (input color, output action)
10. String palindrome checker (reverse and compare)

**🔴 Hard**

11. Password strength checker with multiple criteria
12. Temperature classification (freezing, cold, cool, warm, hot)
13. Age group classifier with nested conditions
14. Multi-condition discount calculator (age, purchase amount, loyalty)
15. Complex string validation (multiple string methods)

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| Using `=` instead of `==` in if | `if age == 18:` not `if age = 18:` | `=` assigns, `==` compares |
| Forgetting to convert input to number | `age = int(input(...))` | input() returns string, causes type errors |
| String concatenation with numbers | `"Age: " + str(age)` or use f-string | Can't mix types without conversion |
| Case sensitivity in comparison | Use `.lower()` for case-insensitive | "Hello" != "hello" in Python |
| Incorrect logical operator | AND/OR logic matters in conditions | `and` is stricter than `or` |
| Missing elif (using multiple if) | Use elif for mutually exclusive conditions | Multiple if statements all execute |
| Wrong operator precedence | Use parentheses to be clear | Unclear order: `and` before `or` |
| Forgetting colons after if/else | Always end with `:` | Syntax error otherwise |

---



### 📌 Key Takeaways (Day 1)

💡 **print() is your window to output** — Master it first!  
💡 **Variables are containers** — They hold data of different types  
💡 **Type matters** — Python cares about int vs string vs float  
💡 **Operators do different things** — `+` adds numbers but joins strings  
💡 **if-elif-else controls flow** — One path executes at a time  
💡 **Logical operators combine conditions** — and/or/not build complex decisions  
💡 **input() always returns strings** — Convert immediately if needed!  
💡 **String methods are powerful** — They transform and analyze text  

---

## Day 2: Loops & Iterations, Lists & Tuples, Dictionary

**Difficulty**: 🟡 **Medium** | **File**: `day2.ipynb`

### 🎯 What You'll Learn
- Master **for loops** for iterating sequences and ranges
- Understand **while loops** for condition-based repetition
- Control loops with **break**
- Create and manipulate **lists**: append, sort, reverse, count, search
- Combine lists with **concatenation** (`+`)
- Work with **tuples** for fixed, ordered data
- Create and use **dictionaries**: update, values(), items(), get()
- Build collections dynamically from **user input inside loops**
- Solve real problems: multiplication tables, permutations, frequency counters

### 📚 Concepts Explained

#### For Loops

The **`for` loop** repeats a block of code for each item in a sequence — most commonly used with `range()`.

```python
num = int(input("Enter a num: "))

for i in range(1, 11):
    print(f"{num} x {i} = {num * i}")
```

**Key Features:**
- 🔁 `range(1, 11)` generates numbers 1 through 10 (stop value excluded)
- 🎯 Great for a known number of repetitions
- ➕ Works directly on lists, strings, dictionaries, and any iterable

---

#### While Loops & `break`

A **`while` loop** repeats as long as a condition is `True`. **`break`** exits the loop early, regardless of the condition.

```python
i = 0
while(i <= 5):
    i += 1
    if(i == 3):
        break
    print(i)
# Output: 1  2   (loop stops before printing 3)
```

**Key Features:**
- 🔄 Use `while` when you don't know the number of iterations in advance
- ⛔ `break` immediately exits the nearest loop
- ⚠️ Always update the loop variable inside the loop, or you'll get an infinite loop

---

#### Lists — Creating, Appending & Combining

A **list** is an ordered, mutable collection.

```python
mov1 = input("Enter your fav movie 1: ")
mov2 = input("Enter your fav movie 2: ")
mov3 = input("Enter your fav movie 3: ")

movieList = []
movieList.append(mov1)
movieList.append(mov2)
movieList.append(mov3)
print(movieList)
```

**Faster input using `map()` + `split()`:**
```python
moviesList = list(map(str, input().split()))
print(moviesList)
```

**Concatenating two lists:**
```python
a = [1, 2]
b = [3, 4]
print(a + b)   # [1, 2, 3, 4]
```

---

#### Lists — Built-in Methods

```python
arr = [100, 20, 30, 40, 50]

arr.reverse()          # Reverses in place, returns None
print(arr)              # [50, 40, 30, 20, 100]

arr.sort(reverse=True)  # Sorts in place, returns None
print(arr)

print(arr.count(20))    # Counts occurrences of 20
```

**Key Features:**
- 🔧 `.reverse()`, `.sort()`, `.append()` all modify the list **in place** and return `None`
- 🚫 Never do `arr = arr.sort()` — it will make `arr` equal to `None`

---

#### Lists — Generating & Searching

```python
arr = []
n = 10
for i in range(1, n + 1):
    arr.append(i * i)     # squares: 1, 4, 9, 16 ... 100

target = int(input("Enter the number you want to search: "))

if target in arr:
    print(f"Target Found at index {arr.index(target)}")
else:
    print("Target NOT Found")
```

**Key Features:**
- 🔍 `in` checks membership (returns `True`/`False`)
- 📍 `.index(value)` returns the position of the first match

---

#### Loops — Sum of N Numbers

```python
n = int(input("Enter n: "))
total = 0

for i in range(n + 1):
    total += i

print(f"Sum = {total}")
```

---

#### Loops — Permutation (nPr) using Factorials

```python
n = int(input("Enter n: "))
r = int(input("Enter r: "))

fact = 1
for i in range(1, n + 1):
    fact *= i
num = fact

fact = 1
denom = n - r
for i in range(1, denom + 1):
    fact *= i
denom = fact

perm = num / denom
print(f"Permutation = {perm}")
```

**Key Features:**
- 🧮 Demonstrates reusing loops to compute factorials for a formula (nPr = n! / (n-r)!)
- 🔁 Same loop pattern used twice for two different factorials

---

#### Tuples — Storing Fixed Data

A **tuple** is like a list but **immutable** — once created, it can't be changed.

```python
name = input("Enter your name: ")
age = input("Enter your age: ")
branch = input("Enter your branch: ")

tup = (name, age, branch)
print(f"Name: {tup[0]}, Age: {tup[1]}, Branch: {tup[2]}")
```

**Key Features:**
- 🔒 Tuples are indexed like lists (`tup[0]`, `tup[1]`...) but can't be modified after creation
- 📦 Good for grouping related, fixed values together

---

#### Dictionaries — Structure, Update & Access

A **dictionary** stores data as **key-value pairs**.

```python
myDict = {
    'name': "Ruchit",
    'marks': {
        'python': 99,
        'webDev': 342,
        'Java': 2
    }
}

myDict.update({'isTrainer': True})   # Add a new key-value pair

for i in myDict.values():
    print(i)

for i in myDict.items():
    print(i[1])   # i is a (key, value) tuple

print(myDict.get('names'))   # None — get() is safe, won't crash
# print(myDict['names'])     # This would raise a KeyError
```

**Key Features:**
- 🗂️ Dictionaries can be **nested** (a dict inside a dict)
- ➕ `.update({key: value})` adds or overwrites a key
- 🛡️ `.get(key)` returns `None` instead of crashing if the key doesn't exist — safer than `dict[key]`
- 🔁 `.values()` iterates values, `.items()` iterates `(key, value)` pairs

---

#### Dictionaries — Building Dynamically in a Loop

```python
myDict = {}

for i in range(3):
    sub = input(f"Enter subject{i+1} name: ")
    marks = int(input(f"Enter marks of {sub}: "))
    myDict.update({sub: marks})

print(myDict)
```

**Key Features:**
- 🔁 Looping instead of writing repetitive `input()` calls follows the **DRY principle**
- 📦 Builds up a dictionary one key-value pair at a time

---

#### Dictionaries — Frequency Counter

A very common real-world pattern: counting how many times each item appears.

```python
arr = [1, 1, 2, 1, 3, 4, 1, 3, 4]
freqCalc = {}

for i in range(len(arr)):
    if arr[i] in freqCalc:
        freqCalc.update({arr[i]: freqCalc[arr[i]] + 1})
    else:
        freqCalc.update({arr[i]: 1})

print(freqCalc)
# Output: {1: 4, 2: 1, 3: 2, 4: 2}
```

**Key Features:**
- 🧮 Classic "counter" pattern — check if key exists, increment or initialize
- 🔑 Keys don't need to be strings — here they're integers

---

### 💻 Key Code Snippets from Day 2

#### Multiplication Table
```python
num = int(input("Enter a num: "))
for i in range(1, 11):
    print(f"{num} x {i} = {num * i}")
```

#### While Loop with Break
```python
i = 0
while(i <= 5):
    i += 1
    if(i == 3):
        break
    print(i)
```

#### List Search
```python
target = int(input("Enter the number you want to search: "))
if target in arr:
    print(f"Target Found at index {arr.index(target)}")
else:
    print("Target NOT Found")
```

#### Frequency Counter
```python
freqCalc = {}
for i in range(len(arr)):
    if arr[i] in freqCalc:
        freqCalc.update({arr[i]: freqCalc[arr[i]] + 1})
    else:
        freqCalc.update({arr[i]: 1})
print(freqCalc)
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Notes |
|-----------|---------|--------|-------|
| **Append to list** | `arr.append(6)` | Adds `6` to end | Modifies in place |
| **Reverse list** | `arr.reverse()` | Reverses order | Returns `None` |
| **Sort list (desc)** | `arr.sort(reverse=True)` | Sorted descending | Returns `None` |
| **Count in list** | `arr.count(x)` | Number of occurrences | — |
| **Search in list** | `x in arr` | `True`/`False` | Membership check |
| **Find index** | `arr.index(x)` | Position of `x` | Raises error if not found |
| **List concat** | `a + b` | Combined list | Creates a new list |
| **Dict update** | `d.update({k: v})` | Adds/overwrites key | — |
| **Dict safe access** | `d.get(k)` | Value or `None` | Won't raise `KeyError` |
| **Dict iterate values** | `d.values()` | All values | — |
| **Dict iterate pairs** | `d.items()` | `(key, value)` pairs | — |

---

### 🧪 Practice Problems (Day 2)

**🟢 Easy**
1. Print a multiplication table for a user-given number
2. Sum all numbers from 1 to N using a loop
3. Reverse a list using `.reverse()`
4. Search whether a number exists in a list using `in`

**🟡 Medium**

5. Build a list of movies from 3 separate inputs using `.append()`
6. Take space-separated input and convert it into a list using `split()`
7. Store a person's name, age, and branch in a tuple and print using indexing
8. Build a dictionary of 3 subjects and marks using a loop instead of repeating code

**🔴 Hard**

9. Calculate permutation (nPr) using factorial logic with nested loops
10. Build a frequency counter dictionary from a list with duplicate values
11. Generate a list of squares (1² to N²) then search for a target and return its index

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| `arr = arr.sort()` | Just call `arr.sort()` on its own line | In-place methods return `None`, overwriting your list |
| `for i in arr: print(arr[i])` | `for i in arr: print(i)` | `i` is already the *value*, not the index — using it as an index can throw `IndexError` |
| `dict['missing_key']` | `dict.get('missing_key')` | `[]` raises `KeyError`; `.get()` returns `None` safely |
| Forgetting loop variable update in `while` | Always update the condition variable inside the loop | Otherwise causes an infinite loop |
| Re-typing input 3+ times | Use a `for` loop to collect repeated input | DRY principle — less code, fewer bugs |

---

### 📌 Key Takeaways (Day 2)

💡 **`for` loops are for known counts, `while` loops are for conditions** — pick based on what you're repeating<br>
💡 **`break` exits a loop immediately** — useful for early stopping<br>
💡 **List methods like `.sort()` and `.reverse()` return `None`** — they change the list, don't replace it<br>
💡 **`in` and `.index()` make searching lists simple** — no manual loop needed<br>
💡 **Tuples are like locked lists** — great for fixed, related data<br>
💡 **`.get()` is safer than `[]` for dictionaries** — avoids crashing on missing keys<br>
💡 **Loops + dictionaries = powerful patterns** — like building a frequency counter in a few lines<br>
💡 **DRY your input code** — loops beat copy-pasting `input()` three times<br>

## Day 3: Sets, Functions & Scope, Recursion

**Difficulty**: 🟡 **Medium** | **File**: `day3.ipynb`

### 🎯 What You'll Learn
- Create and use **sets** (unordered, unique elements)
- Combine **sets, tuples, and lists** to solve real grouping problems
- Define **functions** with `def`, parameters, and `return`
- Understand **functions calling other functions**
- Grasp **scope** — variables local to a function vs. the outside world
- Understand **recursion**: a function calling itself
- Visualize the **implicit call stack** — how recursive calls stack up and unwind
- Trace execution order with "before" and "after" print statements

### 📚 Concepts Explained

#### Bonus: Form Validator (Conditionals Recap)

A warm-up problem combining string checks and flags — validates a name, email, and password using multiple independent conditions before confirming a submission.

> **Question:** Take a user's full name, email, and password as input. Validate that: the full name contains a space (i.e., has a first and last name), the email contains `@` and ends with `.com`, and the password is at least 6 characters long with no spaces. If all checks pass, confirm the form was submitted successfully; otherwise print which parts failed.

```python
name = input("Enter your Name: ").strip()
email = input("Enter your Email: ")
password = input("Enter your Password: ")
flag = True

if ' ' not in name:
    flag = False
    print("Invalid Full Name")

if '@' not in email or not email.endswith(".com"):
    flag = False
    print("Invalid Email Address")

if len(password) < 6 or ' ' in password:
    flag = False
    print("Invalid Password")

if flag:
    print("Form Submitted Successfully.")
```

**Key Features:**
- 🚩 A **flag variable** (`flag = True`) tracks overall validity across multiple independent checks, instead of nesting conditions
- 🔗 Each `if` block runs regardless of the others — every failing rule gets reported, not just the first one
- 🧵 `.strip()` removes leading/trailing whitespace before validation
- 🔤 `.endswith(".com")` checks the tail of a string — useful for format validation

---

#### Sets — Unique, Unordered Collections

A **set** automatically removes duplicates and has no guaranteed order.

```python
newSet = {8, 2, 2, 3, 1, 4}
print(newSet)          # {1, 2, 3, 4, 8}  -> duplicate 2 removed automatically

newSet.add(10)          # Adds an element
newSet.pop()             # Removes an arbitrary element (sets are unordered)
print(newSet)
```

**Key Features:**
- 🚫 Duplicates are automatically discarded
- 🔀 No indexing — order isn't guaranteed, so no `newSet[0]`
- ➕ `.add()` inserts, `.pop()` removes an arbitrary item

---

#### Sets + Tuples + Loops — Grouping & Averaging

A practical combo: use a set to get unique names, then loop through the original data to calculate a value per group.

> **Question:** You're given a list of tuples, where each tuple contains a student's name and their marks. Some names are repeated (a student may appear more than once with different marks). Using a set to identify each unique student, calculate and print the **average marks** for every student — adding up all their marks and dividing by how many times they appear.

```python
studentList = [("Ruchit", 99), ("Vikas", 100), ("Ruchit", 90)]

names = set()
for i in studentList:
    names.add(i[0])          # collect unique student names

for i in names:
    totalSum = 0
    count = 0

    for name, mark in studentList:
        if name == i:
            totalSum += mark
            count += 1

    print(f"Average of {i} = {totalSum / count}")
```

**Key Features:**
- 🧩 Sets are perfect for de-duplicating before grouping
- 🔓 Tuple unpacking directly in a `for` loop: `for name, mark in studentList`
- 📊 A common real-world pattern: group-by + aggregate, without libraries

---

#### Functions — Definition, Parameters & Return

A **function** is a reusable block of code defined with `def`.

```python
def listLen(arr):
    print(len(arr))

arr = [24, 64, 23, 76]
listLen(arr)
```

**Functions that `return` a value (vs. just printing):**
```python
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact

n = 5
print(f"Factorial of {n} = {factorial(n)}")
```

```python
def usdConversionToINR(dollars):
    return dollars * 90

dollars = float(input("Enter the number of dollars: "))
print(f"${dollars} = Rs {usdConversionToINR(dollars)}")
```

**Key Features:**
- 📥 Parameters (`arr`, `n`, `dollars`) let a function work on different inputs
- 📤 `return` sends a value back to the caller — `print()` inside a function does not
- 🔁 A function that returns a value can be reused inside calculations (`factorial(n)`), unlike one that only prints

---

#### Functions Calling Functions — Scope in Action

Functions can call other functions, and each function has its own **local scope** — variables defined inside one function aren't visible in another unless passed in or returned.

```python
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact


def pORc():
    n = int(input("Enter value of n: "))
    r = int(input("Enter value of r: "))
    userInput = int(input("What do you want to perform: \n1. Permutation\n2. Combination = "))

    num = factorial(n)
    denom = factorial(n - r)

    if userInput == 1:
        perm = num / denom
        print(f"Permutation = {perm}")
    elif userInput == 2:
        comb = num / denom * factorial(r)
        print(f"Combination = {comb}")
    else:
        print("Invalid Input")


pORc()
```

**Key Features:**
- 🧠 `pORc()` doesn't know how `factorial()` works internally — it just calls it and uses the result (**abstraction**)
- 🔒 `n`, `r`, `num`, `denom` inside `pORc()` are local to `pORc()` — they don't exist outside it
- ♻️ `factorial()` is reused twice inside the same function, and once more inside the `elif` branch

---

#### Recursion — A Function Calling Itself

**Recursion** is when a function calls itself to solve a smaller version of the same problem. Every recursive function needs a **base case** to stop.

```python
def printNTo1(n):
    if n == 1:
        return          # base case — stops the recursion
    print(n)
    printNTo1(n - 1)     # recursive call — smaller problem

printNTo1(3)
# Output: 3  2
```

**Key Features:**
- 🛑 The `if n == 1: return` is the **base case** — without it, this would recurse forever (`RecursionError`)
- 🔽 Each call works on a smaller input (`n - 1`) moving toward the base case

---

#### The Implicit Call Stack

Every function call is pushed onto a **call stack**. Recursive calls stack up, then unwind in reverse order once the base case is hit — this is why code *before* the recursive call runs top-down, and code *after* it runs bottom-up.

```python
def learningCallStack(n):
    if n == 0:
        return

    print(f"INSIDE Function, BEFORE n = {n}")
    learningCallStack(n - 1)
    print(f"INSIDE Function, AFTER n = {n}")

print("Code Starts")
learningCallStack(3)
print("Learnt Recursion through Call Stack !!!")
```

**Output:**
```
Code Starts
INSIDE Function, BEFORE n = 3
INSIDE Function, BEFORE n = 2
INSIDE Function, BEFORE n = 1
INSIDE Function, AFTER n = 1
INSIDE Function, AFTER n = 2
INSIDE Function, AFTER n = 3
Learnt Recursion through Call Stack !!!
```

**Key Features:**
- 📚 Each call to `learningCallStack()` is **pushed** onto the stack before its recursive call, and **popped** off after it returns
- ⬇️⬆️ "BEFORE" lines print in descending order (3, 2, 1) as calls stack up; "AFTER" lines print in ascending order (1, 2, 3) as they unwind
- 🧠 This is the core mental model for understanding recursion — every recursive call waits, on the stack, for the ones after it to finish

---

#### Recursion with Two Parameters

Recursion doesn't have to count down — it can count up too, and can carry along extra parameters for context (here, the upper limit `n` is passed unchanged through every call).

```python
def print1ToN(i, n):
    if i == n + 1:
        return
    print(i)
    print1ToN(i + 1, n)

print1ToN(1, 5)
# Output: 1  2  3  4  5
```

**Key Features:**
- ⬆️ Counts upward instead of downward by incrementing `i` instead of decrementing `n`
- 🎯 `n` stays constant across all calls — it's just there to define the stopping condition

---

### 💻 Key Code Snippets from Day 3

#### Form Validator
```python
flag = True
if ' ' not in name:
    flag = False
    print("Invalid Full Name")
if '@' not in email or not email.endswith(".com"):
    flag = False
    print("Invalid Email Address")
if len(password) < 6 or ' ' in password:
    flag = False
    print("Invalid Password")
if flag:
    print("Form Submitted Successfully.")
```

#### Set Basics
```python
newSet = {8, 2, 2, 3, 1, 4}
newSet.add(10)
newSet.pop()
print(newSet)
```

#### Group & Average Using Set + Tuples
```python
names = set()
for i in studentList:
    names.add(i[0])

for i in names:
    totalSum, count = 0, 0
    for name, mark in studentList:
        if name == i:
            totalSum += mark
            count += 1
    print(f"Average of {i} = {totalSum / count}")
```

#### Function with Return
```python
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact
```

#### Recursion — Countdown
```python
def printNTo1(n):
    if n == 1:
        return
    print(n)
    printNTo1(n - 1)
```

#### Recursion — Call Stack Demo
```python
def learningCallStack(n):
    if n == 0:
        return
    print(f"BEFORE n = {n}")
    learningCallStack(n - 1)
    print(f"AFTER n = {n}")
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Notes |
|-----------|---------|--------|-------|
| **Create set** | `{1, 2, 2, 3}` | `{1, 2, 3}` | Duplicates auto-removed |
| **Add to set** | `s.add(x)` | Inserts `x` | No effect if already present |
| **Remove from set** | `s.pop()` | Removes an item | Arbitrary — sets are unordered |
| **Define function** | `def f(x): return x` | Reusable block | `return` sends a value back |
| **Call function** | `f(5)` | Runs the function body | Local variables stay inside |
| **Base case** | `if n == 0: return` | Stops recursion | Required in every recursive function |
| **Recursive call** | `f(n - 1)` | Calls itself | Moves toward the base case |

---

### 🧪 Practice Problems (Day 3)

**🟢 Easy**

1. Create a set of numbers with duplicates and print the unique result
2. Write a function that takes a list and prints its length
3. Write a recursive function that counts down from N to 1

**🟡 Medium**

4. Build a form validator that checks a full name (contains a space), an email (`@` and `.com`), and a password (≥6 chars, no spaces), reporting every failing rule
5. Write a function that converts USD to INR and returns the result
6. Use a set to extract unique names from a list of (name, marks) tuples, then calculate each person's average
7. Write a recursive function `print1ToN(i, n)` that counts up from `i` to `n`

**🔴 Hard**

8. Build a function `pORc()` that asks the user for `n`, `r`, and a choice, then calculates Permutation or Combination using a reusable `factorial()` function
9. Trace and print the call stack manually — print a "before" message before the recursive call and an "after" message after it, for `n = 3`, and predict the output order before running it

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| Forgetting a base case in recursion | Always include `if condition: return` | Without it, you get infinite recursion → `RecursionError: maximum recursion depth exceeded` |
| Indexing into a set `s[0]` | Convert to a list first if you need order: `list(s)[0]` | Sets are unordered and unindexed |
| Using `print()` instead of `return` inside a function meant to give a value back | Use `return`, then `print()` the result outside | A function that only prints can't be used in further calculations |
| Assuming variables inside a function exist outside it | Pass values as parameters or `return` them | Function-local variables are out of scope elsewhere |
| Recursive call not moving toward the base case | Make sure the argument changes each call (`n - 1`, `i + 1`) | Otherwise the base case is never reached |

---

### 📌 Key Takeaways (Day 3)

💡 **Sets remove duplicates automatically** — great for uniqueness problems <br>
💡 **Sets + tuples + loops = group-by logic** — no external library needed <br>
💡 **`return` gives a value back; `print()` just displays it** — very different purposes <br>
💡 **Functions can call other functions** — build complex logic from small reusable pieces <br>
💡 **Scope keeps variables contained** — a function's local variables don't leak out <br>
💡 **Every recursive function needs a base case** — or it runs forever <br>
💡 **The call stack explains recursion's order of execution** — calls stack up, then unwind in reverse <br>
💡 **Recursion can count up or down** — the direction depends on how you change the parameter each call <br>


 
## Day 4: Recursion & BackTracking

**Difficulty**: 🟡 **Medium** | **File**: `day4.ipynb`

### 🎯 What You'll Learn
- Continue **recursion** — apply it to iterate over lists
- Understand **backtracking** as an extension of recursion (explore, branch, combine results)
- Solve the classic **"Count Total Paths in a Maze"** problem using recursion
- Solve the **Spiral Matrix** problem using recursive boundary shrinking
- Handle runtime errors gracefully with **try-except**
- Catch **specific exceptions** (`ValueError`, `ZeroDivisionError`) vs. generic ones
- Use **`raise`** to manually trigger a custom exception

### 📚 Concepts Explained

#### Recursion — Iterating Through a List

Recursion can replace a `for` loop — instead of looping, the function calls itself with an incremented index until it reaches the end of the list.

```python
def printElementsOfList(arr, i):
    if i == len(arr):
        return

    print(arr[i])
    printElementsOfList(arr, i + 1)

arr = [10, 20, 12, 31]
printElementsOfList(arr, 0)
```

**Key Features:**
- 🛑 Base case: `i == len(arr)` — stops once every index has been visited
- ⬆️ `i + 1` moves the recursion toward the base case, just like a loop's increment
- 🔁 Any `for` loop over a fixed range can, in principle, be rewritten recursively

---

#### Backtracking — Count Total Paths in a Maze

**Backtracking** is recursion where, at each step, you explore multiple possible choices (branches) and combine their results. This is the classic "count paths from top-left to bottom-right of a grid, moving only right or down" problem.

> **Question:** Given a grid of size `n x m`, count the total number of unique paths from the top-left cell `(0, 0)` to the bottom-right cell `(n-1, m-1)`, if you can only move **right** or **down** at each step.

```python
def countTotalPaths(i, j, n, m):
    # Dead End — went out of bounds
    if i == n or j == m:
        return 0
    # Destination reached
    if i == n - 1 and j == m - 1:
        return 1

    # Move Rightwards
    rightWards = countTotalPaths(i, j + 1, n, m)
    # Move Downwards
    downWards = countTotalPaths(i + 1, j, n, m)
    return rightWards + downWards


n = 3
m = 3
print(f"Total paths = {countTotalPaths(0, 0, n, m)}")
```

**Key Features:**
- 🚧 Two base cases: a **dead end** (out of bounds → `0` paths) and the **destination** (→ `1` path)
- 🌳 Every call branches into two recursive calls (right and down) — this branching is what makes it backtracking, not simple recursion
- ➕ Results from both branches are added together to get the total count

---

#### Backtracking — Spiral Matrix

Print a 2D matrix in spiral order (outer ring first, then shrink inward) using recursion instead of manual loop-counters.

```python
def spiralMatrix(mat, top, left, right, bottom):
    if top > bottom or left > right:
        return

    # TOP -> left to Right
    for i in range(left, right + 1):
        print(mat[top][i], end=" ")

    # RIGHT -> top to bottom
    for i in range(top + 1, bottom + 1):
        print(mat[i][right], end=" ")

    # BOTTOM <- right to left
    for i in range(right - 1, left - 1, -1):
        print(mat[bottom][i], end=" ")

    # LEFT <- bottom to top
    for i in range(bottom - 1, top, -1):
        print(mat[i][left], end=" ")

    spiralMatrix(mat, top + 1, left + 1, right - 1, bottom - 1)


mat = [
    [1,  2,  3,  4],
    [12, 13, 14, 5],
    [11, 16, 15, 6],
    [10,  9,  8, 7],
]

n = len(mat) - 1
m = len(mat[0]) - 1

spiralMatrix(mat, 0, 0, n, m)
```

**Key Features:**
- 🔲 Four boundaries (`top`, `left`, `right`, `bottom`) define the current "ring" of the matrix being printed
- 🌀 Each recursive call shrinks the ring inward by 1 on all four sides: `top+1, left+1, right-1, bottom-1`
- 🛑 Base case: `top > bottom or left > right` — stops once the boundaries cross (no ring left to print)

---

#### Exception Handling — Basic try-except

Wrap risky code in a **`try`** block; if it fails, the matching **`except`** block runs instead of crashing the program.

```python
try:
    a = int(input("Enter a number:"))
    for i in range(1, 11):
        print(a * i)

except ValueError:
    print("Input has to be a number")
```

**Catching the exception object itself with `Exception as e`:**
```python
try:
    a = int(input("Enter a number:"))
    for i in range(1, 11):
        print(a * i)

except Exception as e:
    print("Input has to be a number")
    print(e)
```

**Key Features:**
- 🎯 `except ValueError` only catches that specific error (e.g., typing letters instead of a number)
- 🧾 `except Exception as e` catches *any* exception and lets you inspect the actual error message via `e`
- ⚖️ Prefer specific exceptions over a bare `except Exception` where possible — it avoids silently swallowing unrelated bugs

---

#### Exception Handling — Manually Raising an Exception

**`raise`** lets you manually trigger an exception, even a custom message, instead of waiting for Python to raise one naturally.

```python
try:
    a = int(input("Enter a number:"))
    for i in range(1, 11):
        print(a * i)

except:
    raise KeyError('Naaam nahi daalna h')
```

**Key Features:**
- 🚨 `raise` inside an `except` block re-throws a **different** exception than the one that was caught
- ⚠️ A bare `except:` (no exception type) catches *everything*, including things you might not want to catch — generally avoid unless intentional

---

#### Exception Handling — Multiple `except` Blocks

You can catch different exceptions separately and respond to each with a specific message.

```python
try:
    a = int(input("Enter a number:"))
    b = int(input("Enter another number:"))
    print(a / b)

except ValueError:
    print("Input has to be a number")

except ZeroDivisionError:
    print("Number cannot be divisible by 0.")
```

**Key Features:**
- 🎯 Python checks `except` blocks top-to-bottom and runs the **first matching one**
- 🧩 `ValueError` catches bad input (non-numeric text); `ZeroDivisionError` catches dividing by zero — two completely different failure modes, handled separately
- ✅ This is the most "production-realistic" version of the exercises today — specific, readable error handling

---

### 💻 Key Code Snippets from Day 4

#### Recursive List Printing
```python
def printElementsOfList(arr, i):
    if i == len(arr):
        return

    print(arr[i])

    printElementsOfList(arr, i + 1)
```

#### Count Total Paths (Backtracking)
```python
def countTotalPaths(i, j, n, m):
    if i == n or j == m:
        return 0

    if i == n - 1 and j == m - 1:
        return 1

    return countTotalPaths(i, j + 1, n, m) + countTotalPaths(i + 1, j, n, m)
```

#### Spiral Matrix (Backtracking)
```python
def spiralMatrix(mat, top, left, right, bottom):
    if top > bottom or left > right:
        return

    # print top, right, bottom, left edges...
    spiralMatrix(mat, top + 1, left + 1, right - 1, bottom - 1)
```

#### Multiple Except Blocks
```python
try:
    a = int(input("Enter a number:"))
    b = int(input("Enter another number:"))
    print(a / b)

except ValueError:
    print("Input has to be a number")

except ZeroDivisionError:
    print("Number cannot be divisible by 0.")
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Notes |
|-----------|---------|--------|-------|
| **Base case (stop)** | `if i == len(arr): return` | Ends recursion | Required to avoid infinite recursion |
| **Branching recursion** | `f(i, j+1) + f(i+1, j)` | Combines multiple paths | Core idea of backtracking |
| **Shrinking boundaries** | `spiralMatrix(mat, top+1, ...)` | Recurses on a smaller sub-problem | Common pattern for grid/matrix recursion |
| **Catch specific error** | `except ValueError:` | Runs only for that error type | More precise than catching everything |
| **Catch + inspect error** | `except Exception as e:` | `e` holds the error message | Useful for debugging |
| **Manually raise error** | `raise KeyError('msg')` | Throws a custom exception | Use for intentional, controlled failures |
| **Bare except** | `except:` | Catches all errors | ⚠️ Use sparingly — hides the real error type |

---

### 🧪 Practice Problems (Day 4)

**🟢 Easy**

1. Recursively print all elements of a list without using a `for` loop
2. Write a try-except block that catches invalid (non-numeric) input for a single number
3. Write a try-except block that catches division by zero

**🟡 Medium**

4. Count the total number of unique paths from the top-left to bottom-right of an `n x m` grid, moving only right or down
5. Combine `ValueError` and `ZeroDivisionError` handling in one try block with two separate `except` blocks
6. Use `raise` to manually throw a custom exception inside an `except` block

**🔴 Hard**

7. Print a 2D matrix in spiral order using recursion and four shrinking boundaries (top, left, right, bottom)
8. Modify `countTotalPaths` to also print one valid path (not just count them)
9. Modify `spiralMatrix` to return a list of the spiral-order elements instead of printing them directly

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| Using `&` instead of `and` for logical conditions | `if i == n-1 and j == m-1:` not `i == n-1 & j == m-1` | `&` is bitwise AND with **higher precedence** than `==` in Python — the expression doesn't evaluate the way it looks like it does, and can silently produce wrong results |
| Missing a base case in backtracking | Always define both a "dead end" and a "destination" base case | Without a proper stopping condition, recursive branching never terminates |
| Using a bare `except:` | Catch specific exceptions (`ValueError`, `ZeroDivisionError`, etc.) | Bare `except` hides bugs by catching errors you didn't anticipate |
| Forgetting `except` order matters | Put more specific exceptions before general ones | Python uses the first matching `except` block, top to bottom |
| Confusing `raise` with `except` | `raise` throws a new/custom exception; `except` catches an existing one | They serve opposite purposes and are often used together |

---

### 📌 Key Takeaways (Day 4)

💡 **Recursion can replace loops entirely** — even simple list iteration <br>
💡 **Backtracking = recursion that branches** — explore multiple choices, then combine the results <br>
💡 **Every backtracking problem needs clear base cases** — a "failure" case and a "success" case <br>
💡 **Shrinking boundaries is a common recursive pattern** — especially for grid/matrix problems <br>
💡 **`&` is not `and`** — bitwise operators and logical operators behave very differently in conditions <br>
💡 **`try-except` prevents crashes** — catch errors instead of letting the program stop <br>
💡 **Specific exceptions > bare except** — `ValueError`, `ZeroDivisionError` etc. give clearer, safer error handling <br>
💡 **`raise` lets you throw your own exceptions** — useful for enforcing custom rules <br>

---

## Day 5: Custom Exceptions, `finally`, Classes & Objects

**Difficulty**: 🟡 **Medium** | **File**: `day5.ipynb`

### 🎯 What You'll Learn
- Create **custom exception classes** (e.g., `NegativeNumberError`)
- Understand the **`finally`** keyword and when code inside it always runs
- Use **`map()`** to apply a function to every item in a list
- Understand **classes and objects** — the blueprint vs. the instance
- Grasp **`self`** — what it actually refers to, and when it's created
- Use the **`__init__`** constructor to set up instance attributes
- Define **class attributes** (shared) vs. **instance attributes** (unique per object)
- Write **methods** that operate on an object's own data (`self.attribute`)

### 📚 Concepts Explained

#### Custom Exceptions

Python lets you define your own exception types by creating a class. This makes error handling more descriptive than relying only on built-in exceptions.

```python
class NegativeNumberError():
    pass

try:
    num = int(input("Enter a num: "))

    if num < 0:
        raise NegativeNumberError("Number is Negative !!!")

    print(f"Number = {num}")

except Exception as e:
    print(f"Error = {e}")
```

**Key Features:**
- 🏷️ A custom exception is just a class — giving it a descriptive name makes your `except` blocks self-documenting
- 📝 `except Exception as e` lets you print the actual message passed to `raise`

---

#### The `finally` Keyword

Code inside **`finally`** always runs — whether the `try` block succeeds, fails, or even if an exception isn't caught by any `except`. It's used for cleanup that must happen no matter what (closing files, releasing resources, final logging).

```python
try:
    print(1)

    if 99:
        raise NegativeNumberError

    print(3)

except:
    print("Error")

finally:
    print("Code ENds")
```

**Key Features:**
- ✅ `finally` runs after `try`/`except`, regardless of the outcome
- 🧹 Common use case: closing a file or database connection even if something failed mid-way
- 🔁 Even a `return` inside `try` or `except` won't skip `finally`

---

#### `map()` — Applying a Function to a List

**`map(function, iterable)`** applies a function to every element of a list without writing an explicit loop.

```python
def multiplyBy2(x):
    return x * 2

arr = [4, 5, 7, 2, 6]
res = list(map(multiplyBy2, arr))

print(res)   # [8, 10, 14, 4, 12]
```

**Key Features:**
- 🔁 `map()` returns a **map object** (lazy) — wrap it in `list()` to see the actual results
- 🧩 The function passed to `map()` is applied once per element, replacing a manual `for` loop

---

#### Classes & Objects — The Basics

A **class** is a blueprint; an **object** (or instance) is something built from that blueprint. `self` refers to the specific object being worked on.

```python
class Student:
    name = "Ruchit Goud"
    marks = 96

    def __init__(self):
        print(f"INSIDE = {self}")

s1 = Student()
print(f"OUTSIDE = {s1}")

s2 = Student()
print(f"OUTSIDE = {s2}")
```

**Key Features:**
- 🏗️ `__init__` runs automatically every time a new object is created — it's the **constructor**
- 🪪 `self` printed inside `__init__` matches the object printed outside — they're the exact same object, just referenced from two different places
- 👥 `s1` and `s2` are two separate objects, each with their own identity (different memory address shown when printed), even though the class is the same

---

#### Instance Attributes via `__init__`

Instead of hardcoding values as class attributes, `__init__` can accept parameters and store them per-object using `self.attribute = value`.

```python
class Student:
    clgName = "SBMP"
    training = "Python Basic to OOPS"

    def __init__(self, fullName, age, rollNo):
        self.name = fullName
        self.age = age
        self.rollNo = rollNo

    def hello(self):
        print(f"Welcome Student")

s1 = Student("Ruchit Goud", 20, 18)
s1.hello()
```

**Key Features:**
- 🏫 `clgName` and `training` are **class attributes** — shared identically across every object of this class
- 🎒 `name`, `age`, `rollNo` are **instance attributes** — unique to each object, set through the constructor
- ⚙️ Methods like `hello()` still need `self` as their first parameter, even if they don't use any instance data

---

#### A Full Class Example — Circle

Combining a constructor, instance attributes, and multiple methods that use them.

```python
import math

class Circle:

    def __init__(self, radius):
        self.r = radius

    def area(self):
        print(f"Area of Circle with radius {self.r} = {(math.pi * self.r * self.r):.2f}")

    def perimeter(self):
        print(f"Perimeter of Circle with radius {self.r} = {(math.pi * 2 * self.r):.2f}")

c1 = Circle(int(input("Enter radius for Circle 1: ")))
c2 = Circle(int(input("Enter radius for Circle 2: ")))

c1.area()
c1.perimeter()

print("=========================================")

c2.area()
c2.perimeter()
```

**Key Features:**
- 📐 Both `area()` and `perimeter()` reuse `self.r`, set once in the constructor — no need to pass the radius again
- 🎯 `c1` and `c2` behave completely independently — each has its own `r`, so calling a method on one never affects the other
- 🧮 `math.pi` is used from the built-in `math` module, formatted to 2 decimal places with an f-string

---

### 💻 Key Code Snippets from Day 5

#### Custom Exception + finally
```python
class NegativeNumberError():
    pass

try:
    num = int(input("Enter a num: "))
    if num < 0:
        raise NegativeNumberError("Number is Negative !!!")
    print(f"Number = {num}")
except Exception as e:
    print(f"Error = {e}")
finally:
    print("Code ENds")
```

#### map() with a Custom Function
```python
def multiplyBy2(x):
    return x * 2

arr = [4, 5, 7, 2, 6]
res = list(map(multiplyBy2, arr))
print(res)
```

#### Circle Class
```python
class Circle:
    def __init__(self, radius):
        self.r = radius

    def area(self):
        print(f"Area = {(math.pi * self.r * self.r):.2f}")
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Notes |
|-----------|---------|--------|-------|
| **Custom exception** | `class MyError(): pass` then `raise MyError("msg")` | Custom error type | See ⚠️ Common Mistakes — should inherit `Exception` |
| **finally block** | `finally: print("done")` | Always runs | Runs even after an exception |
| **map()** | `list(map(f, arr))` | New list with `f` applied to each item | Must wrap in `list()` to see results |
| **Define class** | `class Student:` | Blueprint | — |
| **Constructor** | `def __init__(self, ...):` | Runs on object creation | Sets up instance attributes |
| **Instance attribute** | `self.name = name` | Unique per object | — |
| **Class attribute** | `name = "default"` (outside `__init__`) | Shared across all objects | — |
| **Create object** | `s1 = Student(...)` | New instance | Calls `__init__` automatically |

---

### 🧪 Practice Problems (Day 5)

**🟢 Easy**

1. Create a `PositiveNumberError` custom exception, similar to `NegativeNumberError`
2. Use `map()` to square every number in a list
3. Create a `Rectangle` class with `length` and `width`, and a method to print its area

**🟡 Medium**

4. Add a `finally` block to a division try-except that always prints "Calculation attempt finished"
5. Create a `Student` class where `__init__` takes name, age, and 3 subject marks, and a method prints the average
6. Extend the `Circle` class with a method `isBiggerThan(otherCircle)` that compares two circles by area

**🔴 Hard**

7. Create a custom exception hierarchy (e.g., `InvalidAgeError`, `InvalidMarksError`) each with a descriptive message, and validate multiple fields in one try block
8. Build a `BankAccount` class with a constructor for balance, and methods `deposit()`/`withdraw()` that raise a custom `InsufficientFundsError` when needed

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| `class NegativeNumberError(): pass` | `class NegativeNumberError(Exception): pass` | A custom exception **must inherit from `Exception`** (or a subclass of it) — otherwise `raise` will fail with `TypeError: exceptions must derive from BaseException` |
| Forgetting `self` as the first parameter in a method | `def hello(self):` not `def hello():` | Every instance method needs `self` to access that object's data |
| Confusing class attributes with instance attributes | Use `self.x = x` inside `__init__` for per-object data | Class attributes (defined outside `__init__`) are shared — changing one via an instance can have unexpected effects |
| Forgetting `map()` returns a map object, not a list | Wrap with `list(map(...))` | Printing a map object directly shows something like `<map object at 0x...>`, not the values |
| Assuming `finally` only runs on success | Test it with a deliberate error | `finally` runs **regardless** of whether an exception occurred |

---

### 📌 Key Takeaways (Day 5)

💡 **Custom exceptions should inherit from `Exception`** — plain classes can't be raised properly<br>
💡 **`finally` always executes** — perfect for guaranteed cleanup code<br>
💡 **`map()` avoids explicit loops** for applying a function across a list<br>
💡 **A class is a blueprint, an object is a specific instance** built from it<br>
💡 **`self` refers to the current object** — it's how a method knows *which* object's data to use<br>
💡 **`__init__` runs automatically when an object is created** — it's where instance attributes are set up<br>
💡 **Class attributes are shared; instance attributes are personal** — know which one you actually need<br>
💡 **Objects with the same class are still independent** — changing one doesn't affect another<br>

---

## Day 6: The 4 Pillars of OOPS — Inheritance, Abstraction, Encapsulation, Polymorphism

**Difficulty**: 🔴 **Hard** | **File**: `day6.ipynb`

### 🎯 What You'll Learn
- Revise **classes and objects**
- Understand **inheritance** — a child class reusing a parent class's attributes and methods
- Use **`super()`** to call the parent class's constructor and methods from a child class
- Understand **abstraction** using `ABC` and `@abstractmethod`
- Understand **encapsulation** — private attributes/methods using `__` (double underscore)
- Recognize **static methods** and how they differ from regular instance methods
- Understand **dunder (magic) methods** and their role in **polymorphism**
- Apply all of this together in a real **Change Password** system using encapsulation + recursion

### 📚 Concepts Explained

#### Inheritance — Sharing Attributes Across Classes

A **child class** automatically has access to everything defined in its **parent class**, without rewriting it.

```python
class Shape:
    sides = "No idea"

class Triangle(Shape):
    demo = "checking"

class RightAngledTriangle(Triangle):
    abc = "abc"

class Isosceles(Triangle):
    defg = "abcdefg"

t1 = Triangle()
print(t1.sides)        # "No idea" — inherited from Shape

r1 = RightAngledTriangle()
print(r1.sides)        # Also inherited — multi-level inheritance

i1 = Isosceles()
print(i1.defg)
```

**Key Features:**
- 🧬 `Triangle(Shape)` means `Triangle` inherits everything `Shape` has
- 🔗 Inheritance can chain multiple levels deep — `RightAngledTriangle` inherits from `Triangle`, which inherits from `Shape`, so it gets `sides` too
- 🌳 Each subclass can still define its own unique attributes on top of what it inherits

---

#### Inheritance with `super()`

When a child class has its **own** `__init__`, it needs to explicitly call the parent's constructor using `super()` — otherwise the parent's setup never runs.

```python
class Employee:
    def __init__(self, role, dept, salary):
        self.role = role
        self.department = dept
        self.salary = salary

    def showDetails(self):
        print(f"Role: {self.role}")
        print(f"Department: {self.department}")
        print(f"Salary: {self.salary}")


class Engineer(Employee):
    def __init__(self, name, age, role, dept, salary):
        self.name = name
        self.age = age
        super().__init__(role, dept, salary)

    def showDetails(self):
        print(f"Name: {self.name}")
        print(f"Age: {self.age}")
        super().showDetails()


eng1 = Engineer("Ruchit", 20, "DA", "CSE", 80000)
eng1.showDetails()
```

**Key Features:**
- 🏗️ `super().__init__(role, dept, salary)` runs `Employee`'s constructor to set up `role`, `department`, `salary` — no need to repeat that logic in `Engineer`
- 🔁 `super().showDetails()` calls the **parent's version** of the method, then the child can add its own extra details around it
- ♻️ This avoids duplicating code — the child extends the parent instead of rewriting it

---

#### Abstraction — Defining a Contract with `ABC`

**Abstraction** hides implementation details and forces child classes to implement specific methods, using Python's `abc` module.

```python
from abc import ABC, abstractmethod

class Animal(ABC):
    @abstractmethod
    def sound():
        pass

class Dog(Animal):
    def sound(self):
        print("Dog Barks !")

    def food(self):
        print("Eats Pedigree !")

class Cat(Animal):
    pass   # doesn't implement sound() — will error if instantiated

d1 = Dog()
d1.sound()

# c1 = Cat()   # This line would raise: TypeError: Can't instantiate abstract class Cat with abstract method sound
```

**Key Features:**
- 🚫 `Animal` can **never be instantiated directly** — it's an abstract base class (`ABC`)
- 📜 `@abstractmethod` forces every subclass to provide its **own** implementation of `sound()`
- ⚠️ If a subclass (like `Cat`) doesn't implement the abstract method, trying to create an object of it raises a `TypeError`

---

#### Encapsulation — Private Attributes & Methods

**Encapsulation** restricts direct access to an object's internal data. In Python, prefixing a name with `__` (double underscore) makes it "private" via name mangling.

```python
class Account:
    def __init__(self, accNo, accPass):
        self.accNo = accNo
        self.__accPass = accPass

    def __showPass(self):
        print(f"Password = {self.__accPass}")

    def checkPass(self):
        self.__showPass()

a1 = Account(4589132679645, "Ruchit007")
# print(a1.__accPass)     # Would raise AttributeError — not directly accessible
# a1.__showPass()          # Would raise AttributeError — private method
a1.checkPass()             # Works — public method internally calls the private one
```

**Key Features:**
- 🔒 `self.__accPass` and `__showPass()` can't be accessed directly from outside the class (`a1.__accPass` fails)
- 🚪 Public methods like `checkPass()` act as a **controlled gateway** to private data
- 🛡️ This protects sensitive data (like a password) from being read or changed carelessly from outside the class

---

#### Encapsulation in Practice — Change Password System

> **Question:** Build an `Account` class where the password is completely private. Add a method to change the password that first asks for the old password to verify identity, then asks for a new password twice (to confirm it was typed correctly). If the old password is wrong, ask again. If the new password and confirmation don't match, ask again.

```python
class Account:
    def __init__(self, accNum, accPass):
        self.accNum = accNum
        self.__accPass = accPass

    def __showPass(self):
        return self.__accPass

    def checkPass(self):
        print(self.__showPass())

    def changePassword(self):
        oldPass = input("Enter your old Password: ")

        if oldPass == self.__showPass():
            while True:
                newPass = input("Enter New Password: ")
                confirmPass = input("Confirm Password: ")

                if newPass == confirmPass:
                    self.__accPass = newPass
                    print("Password changed successfully!")
                    break
                else:
                    print("Password does not match!")
        else:
            print("Wrong Password, Try Again !")
            self.changePassword()


a1 = Account(143164945255, "Ruchit798")
a1.checkPass()
a1.changePassword()
a1.checkPass()
```

**Key Features:**
- 🔐 `__accPass` is never exposed directly — always accessed through private/public methods
- 🔁 `self.changePassword()` calling itself on a wrong password is **recursion**, applied to a real-world OOP scenario (Day 3/4 concept reused here)
- ✅ The `while True` + `break` pattern keeps asking for a new password until it's confirmed correctly
- 🧩 This single example ties together encapsulation, methods, recursion, and control flow

---

#### Static Methods (Introduced)

A **static method** belongs to the class itself rather than any specific object — it doesn't need `self` and can't access instance data. It's marked with `@staticmethod`.

```python
class Student:
    def __init__(self, name):
        self.name = name

    # @staticmethod   <- tried here, but commented out in class since welcomeMsg
    #                     was kept as a regular instance method instead
    def welcomeMsg(self):
        print(f"Welcome Student")

s1 = Student("Ruchit")
s1.welcomeMsg()
```

**Key Features:**
- 🧷 A true static method would be written as:
  ```python
  class Student:
      @staticmethod
      def welcomeMsg():
          print("Welcome Student")

  Student.welcomeMsg()   # called on the class, no object needed
  ```
- ⚖️ Use `@staticmethod` when a method doesn't need `self` or any object-specific data — it's just logically grouped inside the class
- 📌 *Note: this file's active code kept `welcomeMsg` as a normal instance method (the `@staticmethod` line is commented out) — worth revisiting with a full working static-method example in class.*

---

#### Dunder Methods & Polymorphism (Introduced, No Code Yet)

**Dunder ("double underscore") methods** like `__init__`, `__str__`, `__add__`, `__eq__` let your own objects work with Python's built-in syntax (`print()`, `+`, `==`, etc.) — this is a form of **polymorphism**, since the same operator/function behaves differently depending on the object.

*Example of what this typically looks like (not yet in the uploaded file — add your actual in-class example here):*
```python
class Student:
    def __init__(self, name, marks):
        self.name = name
        self.marks = marks

    def __str__(self):
        return f"Student({self.name}, {self.marks} marks)"

    def __add__(self, other):
        return self.marks + other.marks

s1 = Student("Ruchit", 92)
s2 = Student("Vikas", 96)

print(s1)          # Uses __str__ -> Student(Ruchit, 92 marks)
print(s1 + s2)     # Uses __add__ -> 188
```

**Key Features:**
- ✨ `__str__` controls what `print(object)` displays instead of the default `<Student object at 0x...>`
- ➕ `__add__` lets you define what `+` means between two objects of your own class
- 🎭 This is **polymorphism**: the `+` operator behaves differently for `int + int` vs. `Student + Student`, based on what the class defines

---

### 💻 Key Code Snippets from Day 6

#### Inheritance with super()
```python
class Engineer(Employee):
    def __init__(self, name, age, role, dept, salary):
        self.name = name
        self.age = age
        super().__init__(role, dept, salary)

    def showDetails(self):
        print(f"Name: {self.name}")
        super().showDetails()
```

#### Abstraction
```python
from abc import ABC, abstractmethod

class Animal(ABC):
    @abstractmethod
    def sound():
        pass
```

#### Encapsulation
```python
class Account:
    def __init__(self, accNo, accPass):
        self.accNo = accNo
        self.__accPass = accPass
```

#### Change Password (Encapsulation + Recursion)
```python
def changePassword(self):
    oldPass = input("Enter your old Password: ")
    if oldPass == self.__showPass():
        while True:
            newPass = input("Enter New Password: ")
            confirmPass = input("Confirm Password: ")
            if newPass == confirmPass:
                self.__accPass = newPass
                print("Password changed successfully!")
                break
            else:
                print("Password does not match!")
    else:
        print("Wrong Password, Try Again !")
        self.changePassword()
```

---

### 🔢 Common Operations Reference

| Operation | Example | Result | Notes |
|-----------|---------|--------|-------|
| **Inherit a class** | `class Child(Parent):` | Child gets Parent's attributes/methods | Can chain multiple levels |
| **Call parent constructor** | `super().__init__(...)` | Runs Parent's `__init__` | Avoids duplicating setup logic |
| **Call parent method** | `super().method()` | Runs Parent's version | Can be combined with child's own logic |
| **Abstract class** | `class X(ABC):` | Can't be instantiated directly | — |
| **Abstract method** | `@abstractmethod` | Must be implemented by subclasses | Raises `TypeError` if not |
| **Private attribute** | `self.__x = x` | Not accessible as `obj.__x` outside class | Name-mangled internally |
| **Private method** | `def __method(self):` | Not callable as `obj.__method()` outside class | — |
| **Static method** | `@staticmethod` | No `self`, called via `Class.method()` | Doesn't touch instance data |
| **Dunder method** | `def __str__(self): ...` | Customizes built-in behavior | Enables polymorphism |

---

### 🧪 Practice Problems (Day 6)

**🟢 Easy**

1. Create a `Vehicle` parent class and a `Car` child class that inherits from it
2. Create an abstract `Shape` class with an abstract `area()` method
3. Add a private `__balance` attribute to an `Account` class, accessible only via a `getBalance()` method

**🟡 Medium**

4. Use `super()` to extend a `Person` class into a `Teacher` class, adding a `subject` attribute
5. Implement `Dog` and `Cat` classes that both inherit from an abstract `Animal` class and implement `sound()` differently (polymorphism through method overriding)
6. Add a static method `Account.isValidPassword(password)` that checks password length ≥ 6 without needing an object

**🔴 Hard**

7. Extend the password-change system to also validate that the new password isn't the same as the old one
8. Add `__str__` and `__eq__` dunder methods to the `Account` class so printing an account shows account number only (not password), and two accounts can be compared by account number
9. Build a small `Shape` hierarchy (`Shape` abstract → `Circle`, `Rectangle`, `Triangle`) where each implements `area()`, and write a function that takes a list of shapes and prints the total area — demonstrating polymorphism (same method call, different behavior per class)

---

### ⚠️ Common Mistakes

| ❌ Mistake | ✅ Solution | 💭 Why It Matters |
|-----------|-----------|------------------|
| Forgetting `super().__init__()` in a child class | Always call it if the parent needs its own setup | Without it, the parent's attributes never get initialized on the child |
| Trying to instantiate an abstract class | `Animal()` → error; create `Dog()` instead | `ABC` classes are blueprints only — never meant to be created directly |
| Not implementing all abstract methods in a subclass | Implement every `@abstractmethod` from the parent | Otherwise the subclass is *also* considered abstract and can't be instantiated |
| Accessing a private attribute directly (`obj.__x`) | Use a public method to access it (`obj.getX()`) | Double-underscore attributes are name-mangled and not meant for direct outside access |
| Adding `self` to a method meant to be static | Use `@staticmethod` and drop `self` if the method doesn't touch instance data | Keeps the method callable via the class itself, without needing an object |
| Confusing `__init__` with other dunder methods | `__init__` builds the object; `__str__`/`__add__`/etc. customize behavior | Each dunder method controls a different built-in interaction |

---

### 📌 Key Takeaways (Day 6)

💡 **Inheritance lets a child class reuse a parent's code** — write once, extend many times<br>
💡 **`super()` calls the parent's version** of `__init__` or any method — avoids duplicating logic<br>
💡 **Abstraction defines a contract** — `ABC` + `@abstractmethod` force subclasses to implement required behavior<br>
💡 **Encapsulation protects sensitive data** — `__` makes attributes/methods private, accessible only through controlled public methods<br>
💡 **Static methods belong to the class, not the object** — use them when `self` isn't needed<br>
💡 **Dunder methods enable polymorphism** — the same operator/function (`+`, `print()`, `==`) behaves differently depending on the class<br>
💡 **Real problems combine multiple pillars at once** — the password-change system used encapsulation *and* recursion together<br>
💡 **Recursion still applies inside classes** — a method calling itself (`self.changePassword()`) works exactly like a standalone recursive function<br>

---

# 🔧 Reference Materials

## Python Syntax Quick Reference

```python
# COMMENTS
# Single line comment
""" 
Multi-line comment
or docstring
"""

# VARIABLES & TYPES
name = "Ruchit"       # String
age = 20              # Integer
height = 5.10         # Float
is_student = True     # Boolean
items = [1, 2, 3]     # List
values = (1, 2, 3)    # Tuple
scores = {1, 2, 3}    # Set
person = {"name": "Ruchit", "age": 20}  # Dictionary

# PRINT & INPUT
print("Hello")
name = input("Enter name: ")

# OPERATORS
a + b       # Addition
a - b       # Subtraction
a * b       # Multiplication
a / b       # Division (float)
a // b      # Floor division (int)
a % b       # Modulo (remainder)
a ** b      # Exponentiation

a == b      # Equal
a != b      # Not equal
a > b       # Greater than
a < b       # Less than
a >= b      # Greater or equal
a <= b      # Less or equal

a and b     # Logical AND
a or b      # Logical OR
not a       # Logical NOT

# CONDITIONALS (Coming Day 1 ✓)
if condition:
    # code
elif other_condition:
    # code
else:
    # code

# LOOPS (Coming Day 2)
for i in range(5):
    # code
    
while condition:
    # code

# FUNCTIONS (Coming Day 5)
def function_name(param1, param2):
    return result

# LISTS (Coming Day 3)
my_list = [1, 2, 3, 4, 5]
my_list.append(6)
my_list.remove(3)
my_list[0]          # First element
my_list[1:3]        # Slice

# STRINGS (Learned Day 1 ✓)
text = "Hello"
text.lower()        # lowercase
text.upper()        # UPPERCASE
text.replace("H", "J")
text.split(" ")
len(text)           # length
```

---

## Data Types Comparison

|      Type      |    Example   | Mutable| Ordered | Indexed |
|----------------|--------------|--------|---------|---------|
|   **String**   |  `"Hello"`   |   ❌   |   ✅   |   ✅   |
|    **List**    | `[1, 2, 3]`  |   ✅   |   ✅   |   ✅   |
|   **Tuple**    | `(1, 2, 3)`  |   ❌   |   ✅   |   ✅   |
| **Dictionary** | `{"a": 1}`   |   ✅   |   ✅   |   ✅   | (keys)
|    **Set**     | `{1, 2, 3}`  |   ✅   |   ❌   |   ❌   |

*Python 3.7+ maintains insertion order for dictionaries

---

## String Formatting

```python
# 1. Old style (not recommended)
"Hello %s, you are %d years old" % ("Ruchit", 20)

# 2. .format() method
"Hello {}, you are {} years old".format("Ruchit", 20)

# 3. f-strings (BEST - use this!)
name = "Ruchit"
age = 20
f"Hello {name}, you are {age} years old"

# Advanced f-string formatting
pi = 3.14159
f"Pi: {pi:.2f}"     # 2 decimal places
f"Binary: {5:b}"    # Binary format
f"Hex: {255:x}"     # Hex format
```

---

## Common Mistakes & Solutions

| ❌ Problem | ✅ Solution |
|-----------|-----------|
| `print(5 + "5")` → TypeError | `print(5 + int("5"))` → 10 |
| `if age = 18:` → SyntaxError | `if age == 18:` → Correct |
| `input()` returns string | `int(input())` to convert |
| `"hello" == "HELLO"` → False | `"hello".lower() == "hello".lower()` → True |
| Case sensitivity matters | Use `.lower()` for case-insensitive comparison |
| Indentation errors | Python cares about spaces! Use 4 spaces |
| Forgetting colons after if/while | Always add `:` at end of control statements |

---

## 💡 Key Programming Concepts

### DRY Principle
**D**on't **R**epeat **Y**ourself

❌ Bad:
```python
print("Welcome User 1")
print("Welcome User 2")
print("Welcome User 3")
print("Welcome User 4")
```

✅ Good:
```python
for i in range(1, 5):
    print(f"Welcome User {i}")
```

### Testing Your Code

Always test with multiple inputs:
```python
# Test with expected input
age = 25  # Should print "Adult"

# Test with edge cases
age = 0   # Edge case: minimum
age = 150 # Edge case: unusual value
age = -5  # Edge case: invalid
```

---

## 🛠️ Useful Tools & Resources

### Python IDEs
- 💻 **VS Code** - Lightweight, free, extensible
- 💻 **PyCharm** - Full-featured, but heavier
- 💻 **Jupyter Notebook** - Great for learning and visualization

### Documentation
- 📖 **Python Official Docs** - [python.org](https://python.org)
- 📖 **Real Python** - [realpython.com](https://realpython.com)
- 📖 **W3Schools** - [w3schools.com/python](https://w3schools.com/python)

---

## 📚 Learning Path

### Week 1: Fundamentals (Days 1-3)
- Day 1: Print, Variables, Data Types, Conditionals ✓ DONE
- Day 2: Loops, Iterations, Lists, Tuples (upcoming)
- Day 3: Dictionaries, Sets (upcoming)

### Week 2: Intermediate (Days 4-6)
- Day 4: Functions, Scope
- Day 5: File Handling, Exceptions
- Day 6: Class and Objects and OOPS

---

## ⚡ Quick Debugging Tips

```python
# 1. Print debug info
print(f"DEBUG: variable = {variable}")

# 2. Check data type
print(f"Type: {type(variable)}")

# 3. Check if variable exists
print(variable)  # Will show error if not defined

# 4. Use assertions for testing
assert age > 0, "Age must be positive"

# 5. Break down complex expressions
# Instead of:
result = (a + b) * (c - d) / e
# Do:
sum_part = a + b
diff_part = c - d
result = (sum_part * diff_part) / e
print(f"Sum: {sum_part}, Diff: {diff_part}, Result: {result}")
```

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### Created By Ruchit Goud

---

[🔝 Back to Top](#-welcome-to-the-7-day-journey-of-mastering-python-basics-)

</div>

