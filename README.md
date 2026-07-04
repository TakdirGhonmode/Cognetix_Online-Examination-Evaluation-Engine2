# Cognetix_Online-Examination-Evaluation-Engine2

## Level 2 - Task 2: Online Examination Evaluation Engine

## Project Overview

The **Online Examination Evaluation Engine** is a Python-based console application that automates the evaluation of multiple-choice examinations. The system loads questions from a JSON file, accepts candidate details and responses, validates inputs, evaluates answers automatically, calculates marks and percentage, determines the pass/fail status, and stores the results in a JSON file for future reference.

This project demonstrates Python fundamentals, modular programming, file handling, exception handling, input validation, and business-rule implementation.

---

## Objective

* Automate the evaluation of online examination responses.
* Validate candidate details and answer inputs.
* Calculate marks and percentage automatically.
* Determine Pass/Fail status based on the passing criteria.
* Store examination results for future reference.

---

## Features

* Candidate Name Validation
* Unique Candidate ID Validation
* Question Loading from JSON File
* Multiple Choice Question (MCQ) Support
* Answer Validation (A, B, C, D)
* Automatic Answer Evaluation
* Score and Percentage Calculation
* Pass/Fail Determination
* Result Summary Generation
* JSON-Based Result Storage
* Exception Handling
* Modular Python Code Structure

---

## Project Structure

```text
Cognetix_Online-Examination-Evaluation-Engine2/
│
├── main.py
├── data_handler.py
├── validation.py
├── evaluator.py
├── questions.json
├── results.json
├── README.md
└── venv/
```

---

## Technologies Used

* Python 3
* JSON
* File Handling
* Functions
* Lists
* Dictionaries
* Conditional Statements
* Loops
* Exception Handling

---

## Functional Workflow

1. Load questions from `questions.json`.
2. Accept candidate name and unique candidate ID.
3. Display questions one by one.
4. Validate candidate details and responses.
5. Compare responses with the correct answer key.
6. Calculate:

   * Correct Answers
   * Wrong Answers
   * Obtained Marks
   * Maximum Marks
   * Percentage
7. Determine Pass or Fail.
8. Display the result summary.
9. Save the result to `results.json`.

---

## Validation Rules

### Candidate Name

* Cannot be empty.
* Only letters and spaces are allowed.

### Candidate ID

* Cannot be empty.
* Must contain only numeric values.
* Must be unique.

### Candidate Answers

* Only A, B, C, or D are accepted.
* Invalid answers are rejected until a valid option is entered.

---

## Scoring System

* Correct Answer = 1 Mark
* Wrong Answer = 0 Marks
* Negative Marking = Not Applied

### Percentage Formula

```text
Percentage = (Obtained Marks / Maximum Marks) × 100
```

---

## Pass/Fail Criteria

* Percentage ≥ 40% → Pass
* Percentage < 40% → Fail

---

## Sample Output

```text
========== ONLINE EXAMINATION ==========

Enter Candidate Name: Takdir
Enter Candidate ID: 101

Question 1
Python is a ______ language.

A. Programming
B. Database
C. Browser
D. Operating System

Enter Your Answer: A

...

========== RESULT ==========

Candidate Name   : Takdir
Candidate ID     : 101
Correct Answers  : 9
Wrong Answers    : 1
Obtained Marks   : 9
Maximum Marks    : 10
Percentage       : 90.0%
Status           : Pass

============================
```

---

## Python Concepts Used

* Functions
* Lists
* Dictionaries
* Loops
* Conditional Statements
* JSON File Handling
* Exception Handling
* Input Validation
* Business Logic
* Modular Programming

---

## Future Enhancements

* Negative Marking
* Examination Timer
* Random Question Generation
* SQLite Database Integration
* CSV Export
* Login Authentication
* Graphical User Interface (GUI)
* Multiple Subjects Support

---

## Learning Outcomes

This project demonstrates the ability to:

* Build modular Python applications.
* Implement automated examination evaluation.
* Validate user input using business rules.
* Read and write JSON files.
* Handle exceptions gracefully.
* Store examination records persistently.
* Develop reliable console-based applications.

---

## Author

**GHONMODE TAKDIR MAHENDRA**

**Internship Project – Cognetix**
