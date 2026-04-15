# 🧩 CSP-Based Sudoku Solver (AI Assignment 05)

## 📚 Overview

This repository contains a complete implementation of a **Constraint Satisfaction Problem (CSP)** based Sudoku solver developed for an Artificial Intelligence course.

The solver is capable of solving Sudoku puzzles of varying difficulty levels using advanced AI techniques such as **Backtracking Search**, **Forward Checking**, and **Arc Consistency (AC-3)**.

---

## 🧠 Concepts Implemented

* Constraint Satisfaction Problems (CSP)
* Backtracking Search Algorithm
* Forward Checking
* Arc Consistency (AC-3)
* Minimum Remaining Values (MRV) Heuristic

---

## 🚀 Features

* Solves standard **9x9 Sudoku puzzles**
* Supports multiple difficulty levels:

  * Easy
  * Medium
  * Hard
  * Very Hard
* Reads input from text files
* Automatically generates required puzzle files
* Efficient solving using constraint propagation
* Tracks performance metrics:

  * Number of backtracking calls
  * Number of backtracking failures
  * Execution time

---

## 📂 Project Structure

```
├── easy.txt
├── medium.txt
├── hard.txt
├── veryhard.txt
├── sudoku_solver.py
└── README.md
```

---

## 🛠️ Technologies Used

* Python 3
* Standard Libraries:

  * copy
  * time
  * collections (deque)
  * os

---

## 📥 Input Format

* Each Sudoku board is stored in a `.txt` file
* File contains exactly **9 lines**
* Each line contains **9 digits (0–9)**
* `0` represents an empty cell

### Example:

```
004030050
609400000
005100489
000060930
300807002
026040000
453009600
000004705
090050200
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the project folder:

```
cd your-repo-name
```

3. Run the program:

```
python sudoku_solver.py
```

---

## 📊 Output

For each Sudoku board, the program displays:

* Solved Sudoku grid
* Execution time
* Number of backtracking calls
* Number of failures

---

## 📈 Performance Insight

* Easy puzzles are solved with minimal backtracking due to strong constraint propagation.
* Medium and hard puzzles require more search and constraint checks.
* Very hard puzzles involve deeper recursion and higher computational effort.

---

## 🎯 Learning Outcomes

This project demonstrates:

* How CSPs are applied to real-world problems like Sudoku
* The effectiveness of constraint propagation techniques
* The impact of heuristics like MRV on performance optimization

---

## 🔗 Repository Link

(Add your GitHub repo link here)

---

## 👨‍💻 Author

**Muhammad Abdullah**
BS Artificial Intelligence

---

## 📌 Note

This project was developed as part of an academic assignment. The implementation focuses on clarity, correctness, and application of AI concepts.

---
