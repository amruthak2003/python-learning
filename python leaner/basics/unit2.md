Perfect 👍
Below is **COMPLETE UNIT–2 NOTES** with **clear explanations + DEFINITIONS under EACH HEADING**, written in **simple, exam-oriented language** and **GitHub-ready Markdown**.

You can directly save this as **`unit2_notes.md`**.

---

# 🐍 Python Programming – UNIT 2

## Functions, Modules, Exception Handling & File Handling

---

## 1️⃣ Functions in Python

### 📘 Definition

A **function** is a block of reusable code that performs a specific task and executes only when it is called.

---

### 🔹 Built-in Functions

#### 📘 Definition

**Built-in functions** are predefined functions provided by Python and can be used directly without importing any module.

#### Examples

`print()`, `len()`, `type()`, `max()`, `min()`, `sum()`

```python
numbers = [10, 20, 30]
print(len(numbers))
print(max(numbers))
```

---

### 🔹 User-Defined Functions

#### 📘 Definition

A **user-defined function** is a function created by the programmer using the `def` keyword to perform a specific operation.

```python
def add(a, b):
    return a + b

print(add(10, 20))
```

---

## 2️⃣ Lambda Function

### 📘 Definition

A **lambda function** is an anonymous function defined using the `lambda` keyword and contains only a single expression.

```python
square = lambda x: x * x
print(square(5))
```

---

## 3️⃣ map() Function

### 📘 Definition

The **map() function** applies a given function to every element of an iterable and returns a map object.

```python
numbers = [1, 2, 3]
result = list(map(lambda x: x * 2, numbers))
print(result)
```

---

## 4️⃣ filter() Function

### 📘 Definition

The **filter() function** filters elements from an iterable based on a condition and returns only the elements that satisfy the condition.

```python
numbers = [1, 2, 3, 4, 5]
result = list(filter(lambda x: x % 2 == 0, numbers))
print(result)
```

---

## 5️⃣ Recursion

### 📘 Definition

**Recursion** is a process in which a function calls itself until a base condition is reached.

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

---

## 6️⃣ Module

### 📘 Definition

A **module** is a file that contains Python code such as functions, variables, and classes which can be reused in other programs.

---

### 🔹 Built-in Module

#### 📘 Definition

A **built-in module** is a module that comes pre-installed with Python.

```python
import math
print(math.sqrt(16))
```

---

### 🔹 User-Defined Module

#### 📘 Definition

A **user-defined module** is a module created by the programmer to reuse code.

```python
# mymodule.py
def greet():
    print("Hello")
```

```python
import mymodule
mymodule.greet()
```

---

## 7️⃣ Exception Handling

### 📘 Definition

**Exception handling** is a mechanism used to handle runtime errors and prevent program termination.

---

## 8️⃣ try-except Block

### 📘 Definition

The **try-except block** is used to catch and handle exceptions that occur during program execution.

```python
try:
    print(10 / 0)
except ZeroDivisionError:
    print("Division by zero error")
```

---

## 9️⃣ Assert Statement

### 📘 Definition

The **assert statement** is used for debugging and checks whether a condition is true. If false, it raises an `AssertionError`.

```python
age = 18
assert age >= 18
print("Eligible to vote")
```

---

## 🔟 File Handling in Python

### 📘 Definition

**File handling** is the process of performing operations such as opening, reading, writing, updating, renaming, and deleting files.

---

### 🔹 Open File

#### 📘 Definition

The **open() function** is used to open a file in a specified mode.

```python
file = open("data.txt", "r")
```

---

### 🔹 Close File

#### 📘 Definition

The **close() function** is used to close an opened file.

```python
file.close()
```

---

### 🔹 Read File

#### 📘 Definition

Reading a file means retrieving data from a file using methods like `read()`.

```python
file = open("data.txt", "r")
print(file.read())
file.close()
```

---

### 🔹 Write File

#### 📘 Definition

Writing a file means inserting data into a file using write mode.

```python
file = open("data.txt", "w")
file.write("Python File Handling")
file.close()
```

---

### 🔹 Update File

#### 📘 Definition

Updating a file means modifying or appending content to an existing file.

```python
file = open("data.txt", "a")
file.write("\nNew line added")
file.close()
```

---

### 🔹 Rename File

#### 📘 Definition

Renaming a file means changing the name of an existing file using `os.rename()`.

```python
import os
os.rename("data.txt", "newdata.txt")
```

---

### 🔹 Remove File

#### 📘 Definition

Removing a file means deleting a file permanently from the system using `os.remove()`.

```python
import os
os.remove("newdata.txt")
```

---

## 📌 UNIT–2 Exam Tips

✔ Write **definitions first**
✔ Use **simple syntax**
✔ Mention **file modes (r, w, a)**
✔ Avoid unnecessary complexity

---

## 📂 Suggested GitHub Structure

```
unit2/
│── unit2_notes.md
│── unit2_programs.md
│── unit2_definitions.md
```

---

If you want next:
✅ **UNIT-2 MCQs + answers**
✅ **Viva questions with answers**
✅ **UNIT-3 (OOP) notes**
✅ **Printable PDF version**

Just tell me, Amrutha 😊
