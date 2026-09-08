# 🐍 For Loop - Practice Questions

## 📌 Project Overview

This repository is a collection of beginner-friendly Python exercises designed to build a strong understanding of **`for` loops, conditional statements, `break`, and `continue`**.

The exercises cover basic iteration, mathematical calculations, list and string traversal, pattern printing, prime numbers, factorials, and loop-control statements.

This practice helped strengthen my understanding of **Python programming fundamentals and problem-solving using loops**.

---

## 🎯 Objectives

The main objectives of this practice are to:

* Understand the syntax and working of `for` loops.

* Practice using `range()` for iteration.

* Iterate through lists and strings.

* Perform mathematical calculations using loops.

* Understand nested `for` loops.

* Use conditional statements inside loops.

* Understand and apply `break`.

* Understand and apply `continue`.

* Develop logical thinking and problem-solving skills.

---

# 📚 Topics Covered

## 1. Basic `for` Loop

The following exercises were completed:

### 🔹 Numbers and Ranges

* Print numbers from 1 to 20.

* Print odd numbers between 1 and 50.

* Print numbers divisible by 3 between 1 and 100.

### 🔹 Mathematical Operations

* Print the multiplication table of 9.

* Find the sum of numbers from 1 to 50.

* Calculate the factorial of a number.

* Print all prime numbers between 1 and 50.

### 🔹 Lists and Strings

* Print all elements of a list.

* Iterate through a string and print each character.

### 🔹 Pattern Printing

* Create a triangle pattern using stars.

Example:

```text
*
**
***
****
*****
```

---

# 2. `for` Loop with `break` and `continue`

The second section focuses on controlling the execution of loops using `break` and `continue`.

### 🔹 `break`

`break` is used to **terminate the loop completely** when a specified condition is met.

Exercises include:

* Stop when a number is divisible by 7.
* Stop when `"Mango"` is found in a list.
* Stop at the first number divisible by 13.
* Stop when a square becomes greater than 100.
* Stop when the factorial becomes greater than 1000.

Example:

```python
for i in range(1, 11):
    if i % 7 == 0:
        break
    print(i)
```

### 🔹 `continue`

`continue` is used to **skip the current iteration** and move to the next iteration.

Exercises include:

* Skip all odd numbers.
  
* Skip vowels in a string.

* Skip marks below 35.

* Skip multiples of 4.

* Skip a specific multiplication-table entry.

Example:

```python
for i in range(1, 21):
    if i % 2 != 0:
        continue
    print(i)
```

---

# 💡 Key Concepts Practiced

| Concept          | Description                                         |
| ---------------- | --------------------------------------------------- |
| `for` loop       | Repeats a block of code for each item in a sequence |
| `range()`        | Generates a sequence of numbers                     |
| `if` statement   | Checks whether a condition is true                  |
| `%` operator     | Finds the remainder after division                  |
| `**` operator    | Performs exponentiation                             |
| `break`          | Completely stops the loop                           |
| `continue`       | Skips the current iteration                         |
| Nested loop      | A loop inside another loop                          |
| List iteration   | Accesses each element of a list                     |
| String iteration | Accesses each character of a string                 |

---

# 🧠 Important Learnings

Through these exercises, I learned:

* How `range(start, stop, step)` works.

* Why the stop value in `range()` is excluded.

* How to calculate running totals using a loop.

* How to calculate factorials step by step.

* How nested loops can be used to identify prime numbers.

* How the modulus operator `%` can be used for divisibility checks.

* How `break` and `continue` affect loop execution.

* How to iterate directly through lists and strings.

* How indentation controls the structure of Python loops.

---

# 🛠️ Technologies Used

* **Python 3**

* **Google Colab**

* **Jupyter Notebook**

---

# 📂 Project Structure

```text
Python-For-Loop-Practice/
│
├── Python_For_Loop_Practice.ipynb
└── README.md
```

---

# 📈 Key Takeaway

This practice provided a strong foundation in **Python loops and control flow**.

By solving these exercises, I improved my ability to break a problem into smaller logical steps and implement the solution using Python.

These fundamentals will be useful as I continue learning **Python for Data Analytics**, particularly when working with data processing and automation.

---

⭐ *This repository is part of my ongoing Python learning journey.*

