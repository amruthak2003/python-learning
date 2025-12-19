

# 🐍 Python Fundamentals – Unit 1

## 1️⃣ Introduction to Programming & Python

### What is Programming?

Programming is the process of giving instructions to a computer to perform specific tasks.

### Why Python?

* Easy to learn & read
* Open-source
* Large community support
* Used in Web Development, AI/ML, Data Science, Automation

### Features of Python

* Interpreted language
* High-level language
* Object-oriented
* Platform independent

---

## 2️⃣ Setting the Python Environment

### Install Python

* Download from: [https://www.python.org](https://www.python.org)
* Check installation:

```bash
python --version
```

### Popular IDEs

* VS Code
* PyCharm
* Jupyter Notebook
* IDLE

---

## 3️⃣ Basic Printing in Python

```python
print("Hello, World!")
print("Welcome to Python Programming")
```

### Printing Multiple Values

```python
a = 10
b = 20
print("Sum:", a + b)
```

---

## 4️⃣ Variables & Datatypes

### Variables

* Used to store data
* No need to declare type explicitly

```python
x = 10
name = "Python"
```

### Rules

* Must start with a letter or underscore
* Cannot start with a number
* Case-sensitive

---

## 5️⃣ Numeric Datatypes

| Type    | Example   |
| ------- | --------- |
| int     | 10, -5    |
| float   | 3.14, 2.5 |
| complex | 2+3j      |

```python
a = 10
b = 3.5
c = 2 + 3j
```

---

## 6️⃣ String Datatype

```python
name = "Amrutha"
course = 'Python'
```

### String Operations

```python
print(name.upper())
print(name.lower())
print(name[0])
print(len(name))
```

---

## 7️⃣ List Datatype

* Ordered
* Mutable (can change)

```python
numbers = [1, 2, 3, 4]
names = ["Ram", "Sam", "Tom"]
```

### List Operations

```python
numbers.append(5)
numbers.remove(2)
numbers[0] = 10
```

---

## 8️⃣ Tuple Datatype

* Ordered
* Immutable (cannot change)

```python
t = (1, 2, 3)
```

```python
print(t[0])
```

---

## 9️⃣ Dictionary Datatype

* Key-value pairs

```python
student = {
    "name": "Amrutha",
    "age": 22,
    "course": "Python"
}
```

```python
print(student["name"])
```

---

## 🔟 Set Datatype

* Unordered
* No duplicates

```python
s = {1, 2, 3, 4}
```

```python
s.add(5)
s.remove(2)
```

---

## 1️⃣1️⃣ Operators

### Arithmetic Operators

```python
+  -  *  /  %  **
```

### Relational Operators

```python
==  !=  >  <  >=  <=
```

### Logical Operators

```python
and  or  not
```

---

## 1️⃣2️⃣ Control Structures

### if-else

```python
age = 18
if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible")
```

### Nested if-else

```python
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive Even")
    else:
        print("Positive Odd")
```

---

## 1️⃣3️⃣ While Loop

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

### Nested while

```python
i = 1
while i <= 3:
    j = 1
    while j <= 2:
        print(i, j)
        j += 1
    i += 1
```

---

## 1️⃣4️⃣ For Loop

```python
for i in range(5):
    print(i)
```

### Nested for

```python
for i in range(1, 4):
    for j in range(1, 3):
        print(i, j)
```
📌 Summary

✔ Python Basics
✔ Datatypes
✔ Control Statements
✔ Loops


# 🧑‍💻 Python Fundamentals – Unit 1

## Programming Questions & Answers

---

## 1️⃣ Program to Print Hello World

```python
print("Hello World")
```

---

## 2️⃣ Program to Print Name, Age and Course

```python
name = "Amrutha"
age = 22
course = "Python"

print("Name:", name)
print("Age:", age)
print("Course:", course)
```

---

## 3️⃣ Program to Add Two Numbers

```python
a = 10
b = 20
sum = a + b
print("Sum =", sum)
```

---

## 4️⃣ Program to Find the Largest of Two Numbers

```python
a = 15
b = 10

if a > b:
    print("Largest number is", a)
else:
    print("Largest number is", b)
```

---

## 5️⃣ Program to Check Whether a Number is Even or Odd

```python
num = 7

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

---

## 6️⃣ Program to Check Whether a Number is Positive, Negative or Zero

```python
num = -5

if num > 0:
    print("Positive number")
elif num < 0:
    print("Negative number")
else:
    print("Zero")
```

---

## 7️⃣ Program to Find the Largest of Three Numbers (Nested if)

```python
a = 10
b = 25
c = 15

if a > b:
    if a > c:
        print("Largest is", a)
    else:
        print("Largest is", c)
else:
    if b > c:
        print("Largest is", b)
    else:
        print("Largest is", c)
```

---

## 8️⃣ Program to Print Numbers from 1 to 10 Using while Loop

```python
i = 1
while i <= 10:
    print(i)
    i += 1
```

---

## 9️⃣ Program to Print Numbers from 1 to 10 Using for Loop

```python
for i in range(1, 11):
    print(i)
```

---

## 🔟 Program to Find the Sum of First N Natural Numbers

```python
n = 5
sum = 0

for i in range(1, n + 1):
    sum += i

print("Sum =", sum)
```

---

## 1️⃣1️⃣ Program to Store and Print List Elements

```python
numbers = [10, 20, 30, 40, 50]
print(numbers)
```

---

## 1️⃣2️⃣ Program to Find the Length of a String

```python
text = "Python Programming"
print("Length =", len(text))
```

---

## 1️⃣3️⃣ Program to Access Dictionary Values

```python
student = {
    "name": "Amrutha",
    "age": 22,
    "course": "Python"
}

print(student["name"])
print(student["course"])
```

---

## 1️⃣4️⃣ Program to Add an Element to a Set

```python
s = {1, 2, 3}
s.add(4)
print(s)
```

---

## 1️⃣5️⃣ Program to Print a Multiplication Table

```python
num = 5

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
```

---

## 1️⃣6️⃣ Program to Count Vowels in a String

```python
text = "Python"
count = 0

for ch in text:
    if ch in "aeiouAEIOU":
        count += 1

print("Vowel count =", count)
```

---

## 1️⃣7️⃣ Program to Reverse a String

```python
text = "Python"
print(text[::-1])
```

---

## 1️⃣8️⃣ Program to Find the Largest Number in a List

```python
numbers = [10, 25, 5, 40, 15]
print("Largest =", max(numbers))
```

---

## 1️⃣9️⃣ Program to Print Pattern Using Nested for Loop

```python
for i in range(1, 4):
    for j in range(1, i + 1):
        print("*", end=" ")
    print()
```

---

## 2️⃣0️⃣ Program to Display Keys and Values of Dictionary

```python
student = {
    "name": "Amrutha",
    "age": 22,
    "course": "Python"
}

for key, value in student.items():
    print(key, ":", value)
```

---

## 📌 Tip for Exams

* Write **simple logic**
* Use **proper indentation**
* Avoid unnecessary functions unless asked
* Programs without `input()` are acceptable unless specified

---

If you want next:
✅ **Same programs with `input()` version**
✅ **MCQs with answers**
✅ **Viva questions + answers**
✅ **Unit-wise PDF notes**

Just tell me 😊

