
# Computational Theory

This repository contains my submission for the Computational Theory module, part of the final year Software Development degree at ATU Galway. All solutions are implemented in a Jupyter Notebook and are designed to demonstrate a clear understanding of foundational computational theory concepts.

---

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Task Overview](#task-overview)
- [Features](#features)
- [Libraries Used](#libraries-used)
- [Timeline and History of Commits](#timeline-and-history-of-commits)
- [How to View the Project](#how-to-view-the-project)
- [Criteria for Evaluation Covered](#criteria-for-evaluation-covered)
- [AI Used](#ai-used)
- [References](#references)

---

## Introduction

This notebook demonstrates and explores key ideas in computational theory, including:

- Bitwise operations and binary manipulation
- Hashing functions and SHA-256 padding
- Turing Machine logic and simulation
- Prime number generation and root extraction
- Proof-of-work concept using SHA-256
- Algorithm complexity through bubble sort analysis

Each task includes:
- Python implementation
- Plain English explanation
- Outputs for validation

---

## Repository Structure

```
├── tasks.ipynb          # Main notebook containing all task solutions
├── README.md            # Overview and guide to the repository
├── .gitignore           # Specifies files to ignore in version control
├── requirements.txt     # Lists libraries needed to run the notebook
├── test.txt             # Sample input for SHA-256 padding
├── words.txt            # Word list used in the Proof of Work task
```

---

## Task Overview

| Task | Title                       | Key Components                                                                 |
|------|-----------------------------|---------------------------------------------------------------------------------|
| 1    | Binary Representations      | Bitwise logic: `rotl`, `rotr`, `ch`, `maj` — used in hashing                    |
| 2    | Hash Functions              | Custom C-style hash function in Python, use of constants 31 and 101            |
| 3    | SHA-256 Padding             | Manual bit padding, binary message length appending                            |
| 4    | Prime Numbers               | Trial Division vs. Sieve of Eratosthenes + performance comparison              |
| 5    | Roots                       | Square roots of primes, fractional extraction, binary representation           |
| 6    | Proof of Work               | SHA-256 hash of words, searching for leading zero bits in hashes               |
| 7    | Turing Machine              | Binary addition using simulated Turing logic                                   |
| 8    | Computational Complexity    | Bubble sort analysis across all permutations of [1,2,3,4,5]                     |

---

## Features

- Clear narrative in the notebook using markdown cells to guide the reader through the thought process and solution.
- Python code follows PEP8 standards with clean formatting and meaningful variable names.
- Where relevant, references, research, and reasoning are included to support decisions.
- Frequent and incremental commits showcase steady progress, including revisions and refinements.

---

## Libraries Used

The following standard and approved external Python libraries were used in this project:

- `math`
- `hashlib`
- `itertools`
- `os`
- `time`
- `requests`
- `nltk` (Natural Language Toolkit)

All libraries used are either part of the Python Standard Library or approved for use in the assessment brief.

---

## Timeline and History of Commits

As shown in the Git commit log, work started early in the semester and moved forward every week. Meaningful commit messages keep track of all the big steps and changes.

---

## How to View the Project

The notebook can be viewed directly on GitHub, or you can clone the repository and run it locally:

```bash
git clone https://github.com/FordeTimmy/computational_theory.git
cd computational_theory
jupyter notebook tasks.ipynb
```

Or visit the project on GitHub: [https://github.com/FordeTimmy/computational_theory](https://github.com/FordeTimmy/computational_theory)

---

## Criteria for Evaluation Covered

| Category     | Evidence                                                                 |
|--------------|--------------------------------------------------------------------------|
| Presentation | Well-structured repo, clear markdown, clean file organization            |
| Research     | References and additional explanations included in markdown              |
| Documentation| Detailed markdown cells and code comments                                |
| Development  | Efficient and correct code, broken into logical steps                    |
| Consistency  | Regular commits show progress and iterative improvements                 |


## References

All references and sources used are included in the Markdown sections of `tasks.ipynb`.
