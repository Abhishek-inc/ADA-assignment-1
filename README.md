# Analysis and Design of Algorithms Lab - Assignment 1

**Course:** Analysis and Design of Algorithms Lab  
**Course Code:** ENCS256  
**Program:** B.Tech (CSE) with specialization in Data Science – Semester IV  
**Session:** 2025–26  

## Overview
This assignment focuses on understanding algorithm efficiency through empirical analysis.
The objective is to study how different algorithms scale with input size and to validate
theoretical time complexities using experimental results.

The assignment covers:
- Algorithm growth observation
- Best, average, and worst case analysis
- Recursive algorithms and recurrence relations
- Validation of asymptotic complexity using plots and measurements

All experiments are implemented using Python and executed in a Jupyter Notebook.

---

## Assignment Tasks

### Task 1: Algorithm Growth Observation
- Implemented algorithms with:
  - Constant time O(1)
  - Logarithmic time O(log n)
  - Linear time O(n)
  - Quadratic time O(n²)
- Execution time measured for increasing input sizes
- Results visualized using plots (log-scale used for clarity)

### Task 2: Best, Average, and Worst Case Analysis
- Implemented:
  - Linear Search
  - Binary Search
- Execution time measured for best, average, and worst cases
- Performance compared using plots

### Task 3: Recursion and Recurrence Validation
- Implemented:
  - Factorial (recursive)
  - Fibonacci (naive recursion)
  - Fibonacci (dynamic programming)
- Function call counts and execution times compared
- Demonstrates the benefit of optimization using memoization

### Task 4: Solving Recurrences Through Code
- Implemented recursive functions corresponding to:
  - T(n) = T(n/2) + n
  - T(n) = 2T(n/2) + n
- Recursive call growth analyzed and validated against theoretical complexity

---

## Project Structure

├── analysis.ipynb # Jupyter Notebook containing all tasks
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies
└── plots/ # Generated plots (optional if embedded in notebook)


---

## How to Run

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```
3. Run all cells sequentially to reproduce results and plots.

## Tools & Libraries Used

- Python 3
- Jupyter Notebook
- matplotlib (for plotting)
- standard Python libraries (time, random, functools)

## Observations

The experimental results closely match the theoretical time complexity analysis.
Algorithms with higher asymptotic complexity grow significantly faster with input size,
demonstrating the importance of algorithm selection in real-world applications.

### Author

Name: Abhishek Thakur

Roll Number: 2401420020
