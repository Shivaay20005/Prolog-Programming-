# 🧠 Prolog Programming Language Repository

<div align="center">
  <strong>A comprehensive collection of Prolog implementations for Artificial Intelligence concepts</strong>
</div>

<br>

<div align="center">
  <!-- License -->
  <img src="https://img.shields.io/badge/license-Educational-blue.svg" alt="License">
  <!-- Language -->
  <img src="https://img.shields.io/badge/language-Prolog-orange.svg" alt="Language">
  <!-- Platform -->
  <img src="https://img.shields.io/badge/platform-SWI--Prolog-green.svg" alt="Platform">
  <!-- Status -->
  <img src="https://img.shields.io/badge/status-Active-brightgreen.svg" alt="Status">
</div>

## 📖 Table of Contents

<details>
<summary>Click to expand</summary>
<br>

- [About Prolog](#-about-prolog)
- [Repository Contents](#-repository-contents)
- [Getting Started](#-getting-started)
- [Example Usage](#-example-usage)
- [Academic Context](#-academic-context)
- [Author](#-author)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

</details>

<br>

> **Prolog (Programming in Logic)** is a declarative programming language associated with artificial intelligence and computational linguistics. Programs in Prolog consist of relations and rules rather than sequences of instructions. It excels in pattern matching, symbolic computation, and knowledge representation.

This repository contains implementations of various artificial intelligence algorithms, data structures, and problem-solving techniques using Prolog - a logic programming language particularly well-suited for AI applications.

## 🌟 About Prolog

Prolog stands out among programming languages for its unique approach to problem-solving:

### 🔑 Key Features of Prolog:
- **Declarative programming paradigm** - Describe what you want, not how to get it
- **Built-in pattern matching** - Powerful pattern matching capabilities
- **Backtracking capability** - Automatic search for alternative solutions
- **Unification mechanism** - Intelligent variable binding
- **Natural representation of symbolic knowledge** - Perfect for knowledge-based systems

## 📚 Repository Contents

This repository contains implementations of fundamental algorithms and problems commonly encountered in Artificial Intelligence courses:

<details>
<summary>📊 Click here to see the complete file listing</summary>
<br>

### ➕ Mathematical Functions
- [factorial.pl](factorial.pl) - Computes factorial of a number using recursion
- [fibonacci.pl](fibonacci.pl) - Generates Fibonacci numbers
- [power_calculation.pl](power_calculation.pl) - Calculates powers of numbers
- [multiplication.pl](multiplication.pl) - Implements multiplication using addition
- [sum_two_num.pl](sum_two_num.pl) - Adds two numbers
- [sum_of_list.pl](sum_of_list.pl) - Computes sum of elements in a list
- [maximum_two_num.pl](maximum_two_num.pl) - Finds maximum of two numbers
- [maximum_in_list.pl](maximum_in_list.pl) - Finds maximum element in a list

### 📋 List Operations
- [listreverse.pl](list_reverse.pl) - Reverses a list
- [list_concatenation.pl](list_concatenation.pl) - Concatenates two lists
- [member_check.pl](member_check.pl) - Checks membership of an element in a list
- [insert_at_position.pl](insert_at_position.pl) - Inserts an element at a specific position
- [delete_from_position.pl](delete_from_position.pl) - Deletes an element from a specific position
- [even-odd-length.pl](even-odd-length.pl) - Determines if a list has even or odd length

### 🔍 Search Algorithms
- [a_star_search.pl](a_star_search.pl) - Implementation of A* search algorithm
- [best_first_search.pl](best_first_search.pl) - Best-first search implementation
- [hill_climbing.pl](hill_climbing.pl) - Hill climbing search technique

### 🧩 Classic AI Problems
- [tower_of_hanoi.pl](tower_of_hanoi.pl) - Tower of Hanoi puzzle solution
- [water_jug.pl](water_jug.pl) - Water jug problem solver
- [sudoku.pl](sudoku.pl) - Sudoku puzzle solver using constraint satisfaction
- [family_tree.pl](family_tree.pl) - Family relationship representation and querying
- [enhanced_family_tree.pl](enhanced_family_tree.pl) - Extended family tree with more relationships

### 🧠 Knowledge Representation
- [frames.pl](frames.pl) - Frame-based knowledge representation system
- [cfg_anbn.pl](cfg_anbn.pl) - Context-free grammar for a^n b^n language
- [parse_tree.pl](parse_tree.pl) - Natural language parsing with parse trees

### ⚙️ Utility Files
- [min_max.pl](min_max.pl) - Finds minimum and maximum in a list
</details>

## 🚀 Getting Started

### ✅ Prerequisites
To run these Prolog programs, you need a Prolog interpreter installed:
- [SWI-Prolog](https://www.swi-prolog.org/Download.html) (recommended)
- [GNU Prolog](http://www.gprolog.org/) 
- Other ISO-compliant Prolog systems

### 💾 Installation
1. Install SWI-Prolog from [https://www.swi-prolog.org/Download.html](https://www.swi-prolog.org/Download.html)
2. Clone this repository:
   ```bash
   git clone https://github.com/Shivaay20005/Prolog-Programming-.git
   ```

### ▶️ Running the Programs
1. Open a terminal/command prompt
2. Navigate to the repository directory
3. Start the Prolog interpreter:
   ```bash
   swipl
   ```
4. Load a program:
   ```prolog
   ?- [filename].
   ```
   For example:
   ```prolog
   ?- [factorial].
   ```
5. Query the predicates:
   ```prolog
   ?- factorial(5, F).
   F = 120.
   ```

## 💡 Example Usage

### ➕ Factorial Calculation
```prolog
?- [factorial].
?- factorial(5, Result).
Result = 120.
```

### 👨‍👩‍👧‍👦 Family Relationships
```prolog
?- [family_tree].
?- father(john, Child).
Child = mary ;
Child = tom.
```

### 🗼 Tower of Hanoi
```prolog
?- [tower_of_hanoi].
?- tower_of_hanoi(3).
Move disk from A to C
Move disk from A to B
Move disk from C to B
Move disk from A to C
Move disk from B to A
Move disk from B to C
Move disk from A to C
true.
```

## 🎓 Academic Context

This repository was created as part of the **Artificial Intelligence course curriculum** at Delhi University for 2nd-year students. The programs demonstrate fundamental concepts in AI including:

1. **🧠 Logical Reasoning** - Using Prolog's built-in logical inference engine
2. **🔍 Search Techniques** - Implementing uninformed and informed search algorithms
3. **📚 Knowledge Representation** - Modeling real-world domains using facts and rules
4. **💬 Natural Language Processing** - Parsing sentences and generating parse trees
5. **🧩 Constraint Satisfaction** - Solving problems with constraints (Sudoku)

## 👤 Author

**Shivaay** - Delhi University

## 📄 License

This project is created for **educational purposes** as part of an academic curriculum. Feel free to use these examples for learning Prolog and understanding AI concepts.

<div align="center">
  <img src="https://img.shields.io/badge/license-Educational-blue.svg" alt="License">
</div>

## 🙏 Acknowledgments

- Delhi University Faculty for the Artificial Intelligence course curriculum
- The Prolog community for excellent documentation and resources

---
<div align="center">
  <sub>Built with ❤️ for AI enthusiasts everywhere</sub>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Give%20us%20a%20star%20if%20you%20like%20this%20repo!-%E2%AD%90-yellow" alt="Star Us">
</div>