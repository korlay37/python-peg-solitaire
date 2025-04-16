# 🧩 Peg Solitaire - Python Project

This repository contains a **Peg Solitaire** implementation developed in Python. It is part of my [Udemy course](https://www.udemy.com/) titled **"Python Intermediate/Professional 2025"**, where students can explore practical applications of object-oriented, functional, and modular programming in Python.

## 🎯 Project Description

Peg Solitaire is a classic single-player board game where the goal is to remove all but one peg by jumping over them. This Python version features a text-based interface and allows either manual play or automated random moves.

## ✅ Concepts & Best Practices Used

This project was designed to showcase clean and professional Python practices, including:

- **Object-Oriented Programming (OOP):**  
  Encapsulation and abstraction are demonstrated through the `Solitario` class, which manages game state and logic.
  
- **Closures:**  
  A closure is used to keep track of the number of moves without relying on a global variable.
  
- **Decorators:**  
  A custom decorator logs each game's outcome to a file.

- **Functional Programming:**  
  The use of `map`, `filter`, and `itertools.product` illustrates functional-style coding in Python.

- **Type Hints & Docstrings:**  
  Type annotations and clear docstrings improve code readability and maintainability.

- **Immutable State Handling:**  
  The board is copied before applying moves to avoid unwanted side effects.

- **Clean Code Principles:**  
  Functions are small and focused, with meaningful names and clear responsibilities.

## 🚀 Getting Started

Clone the repository and run the script:

```bash
python peg_solitaire.py
```

You'll be prompted to play manually or let the computer play randomly.

## 📁 Log Output
Every game session logs its outcome (victory/defeat, number of moves, and remaining pegs) to solitario_log.txt.

## 🛠 Requirements
Python 3.9+

No external dependencies

## 📚 License
This project is licensed under the MIT License.
