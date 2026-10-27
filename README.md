
# 🐍 Python Programming Fundamentals
### 🎓 Level 3 Data Technician Bootcamp | Leep Talent

![Python](https://img.shields.io/badge/Python-Programming-3776AB?logo=python&logoColor=white)
![Programming](https://img.shields.io/badge/Skill-Programming%20Fundamentals-blue)
![Logic](https://img.shields.io/badge/Focus-Problem%20Solving-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project was completed as part of my **Level 3 Data Technician Bootcamp with Leep Talent**.

I used **Python** to develop practical programming skills through a series of hands-on exercises involving variables, user input, calculations, conditional statements and loops.

The project focused on understanding programming logic, writing structured code and developing interactive programs that respond to user input.

These exercises provided a foundation for further learning in data analytics, automation and Python-based data processing.

---

## 🎯 Project Objectives

- 🐍 Understand Python programming fundamentals.
- 🧮 Use variables and operators to perform calculations.
- ⌨️ Collect and process user input.
- 🔄 Convert data types using type casting.
- 🔀 Apply conditional statements to make decisions.
- 🔁 Use loops to automate repetitive tasks.
- 💡 Develop logical thinking and problem-solving skills.

---

## 🛠️ Python Skills & Techniques

| Python Concept | Application |
|----------------|-------------|
| Variables | Store and manipulate information |
| `print()` | Display messages and results |
| `input()` | Collect information from users |
| `int()` | Convert values to integers |
| `float()` | Convert values to decimal numbers |
| `str()` | Convert values to strings |
| `if / elif / else` | Make decisions based on conditions |
| `for` loops | Repeat operations over a sequence |
| `while` loops | Repeat operations while conditions are true |
| `range()` | Generate sequences of numbers |
| Arithmetic Operators | Perform mathematical calculations |
| Comparison Operators | Evaluate logical conditions |

---

## 💻 Practical Python Exercises

### 🧮 1. Simple Calculator

Created a calculator that allows users to select mathematical operations and perform calculations.

**Skills Applied:**
- Variables and user input
- Type casting
- Conditional statements
- Arithmetic operations
- While loops

```python
while True:
    print("\nSimple Calculator")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Exit")

    choice = input("Choose an option (1-5): ")

    if choice == "5":
        print("Goodbye!")
        break

    if choice not in ["1", "2", "3", "4"]:
        print("Invalid choice")
        continue

    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    if choice == "1":
        result = num1 + num2
    elif choice == "2":
        result = num1 - num2
    elif choice == "3":
        result = num1 * num2
    else:
        if num2 == 0:
            print("Cannot divide by zero")
            continue
        result = num1 / num2

    print("Result:", result)
```

---

### 🎯 2. Guess the Number Game

Developed an interactive game where users repeatedly guess a predefined number until they get the correct answer.

**Skills Applied:**
- `while` loops
- `if / elif / else`
- User input
- Comparison operators

```python
secret_number = 7

while True:
    guess = int(input("Guess the number: "))

    if guess < secret_number:
        print("Try a little higher!")
    elif guess > secret_number:
        print("Try a little lower!")
    else:
        print("Correct! Well done!")
        break
```

---

### 🔢 3. FizzBuzz Challenge

Used a `for` loop and conditional statements to identify numbers divisible by 3, 5 or both.

**Skills Applied:**
- `for` loops
- `range()`
- Modulus operator `%`
- Conditional statements

```python
for number in range(1, 101):
    if number % 3 == 0 and number % 5 == 0:
        print("FizzBuzz")
    elif number % 3 == 0:
        print("Fizz")
    elif number % 5 == 0:
        print("Buzz")
    else:
        print(number)
```

---

### 📊 4. Sum of Numbers Calculator

Created a program that calculates the sum of integers from 1 up to a number entered by the user.

**Skills Applied:**
- Variables
- Type casting
- User input
- For loops
- Arithmetic calculations

```python
number = int(input("Enter a positive number: "))

if number > 0:
    total = 0

    for i in range(1, number + 1):
        total += i

    print(
        f"The sum of numbers from 1 to {number} is {total}"
    )
else:
    print("Please enter a positive number.")
```

**Example Output:**

```text
Enter a positive number: 10
The sum of numbers from 1 to 10 is 55
```

---

## 🧠 Programming Concepts Demonstrated

### 🔀 Decision-Making

Used conditional statements to control program behaviour based on user choices and logical conditions.

### 🔁 Iteration

Applied `for` and `while` loops to repeat calculations, process sequences and manage interactive programs.

### ⌨️ User Interaction

Used `input()` and `print()` to build programs that communicate with users and respond to their instructions.

### 🧮 Calculations

Performed mathematical operations using variables, arithmetic operators and numeric data types.

---

## 🎯 Learning Outcomes

Through this project, I developed practical experience in:

- ✅ Writing and executing Python scripts
- ✅ Working with variables and data types
- ✅ Collecting and processing user input
- ✅ Performing arithmetic calculations
- ✅ Applying conditional logic
- ✅ Using `for` and `while` loops
- ✅ Building interactive command-line programs
- ✅ Solving programming challenges
- ✅ Developing structured programming skills

---

## 🚀 Tools & Technologies

**Python 3** • **VS Code** • **Variables** • **Conditional Statements** • **Loops** • **User Input** • **Programming Logic**

---

## 📚 Next Steps

Building on these fundamentals, I plan to develop my skills in:

- 🐼 Pandas for data analysis
- 📊 NumPy and data manipulation
- 📈 Matplotlib for data visualisation
- 📂 Reading and processing CSV files
- 🔄 Python automation
- 🤖 Python for Data Science and Machine Learning

---

## 👨‍💻 Project Information

| Detail | Information |
|--------|-------------|
| 🎓 Programme | Level 3 Data Technician Bootcamp |
| 🏫 Training Provider | Leep Talent |
| 🐍 Project | Python Programming Fundamentals |
| 💻 Language | Python 3 |
| 🧠 Focus | Logic, Calculations & User Interaction |
| ✅ Status | Completed |

---

## 💡 Final Reflection

This project helped me understand how Python programs work, from storing values and processing user input to controlling program flow through conditional statements and loops.

Completing these exercises strengthened my confidence in writing code, solving problems and building simple interactive applications.

It also established a foundation for progressing into more advanced Python programming, data analysis and automation.

---

⭐ *Building practical programming and data analytics skills through hands-on learning.*


[link to my google colab task 1](https://colab.research.google.com/drive/1M-x6f_F-2-arhDbLdXlNX3YXrOH9EYZe#scrollTo=RRnOPhgvcJae )

[link to my google colab task 2](https://colab.research.google.com/drive/1CBsrKEyqsoEcnQ43Xp72xKMwne0k2IiB )
