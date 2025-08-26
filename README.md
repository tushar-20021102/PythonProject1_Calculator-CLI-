🧮 Python Project – Command-Line Calculator
📌 Project Overview

This repository presents a progressive learning journey of building a Command-Line Calculator in Python. It begins with a procedural programming approach, then evolves into Object-Oriented Programming (OOP) using instance methods, then static methods, and finally class methods.

This progression helps beginners understand how Python code can evolve from simple scripts into structured and reusable designs using different OOP method types.

🚀 Learning Journey
1️⃣ Procedural Approach – Functions Only

The first version implements a calculator using basic functions (add, subtract, multiply, division).

Focus: Taking input, writing functions, using conditional logic, handling division by zero.

2️⃣ OOP Approach – Using Instance Methods

The second version introduces a Calculator class with methods that require self.

Focus: Understanding classes, objects, and instance methods.

Requires object creation before calling methods.

3️⃣ OOP Approach – Using Static Methods

The third version introduces @staticmethod, allowing methods to be called directly from the class without creating objects.

Focus: Logical grouping of functions inside a class.

No self or cls required.

4️⃣ OOP Approach – Using Class Methods

The fourth version introduces @classmethod, where methods take cls as the first parameter.

Focus: Understanding how class methods can work at the class level while still being callable without objects.

Useful when working with class variables or factory methods.

🧑‍💻 What You’ll Learn

Through these four implementations, you will gain hands-on experience with:

Procedural programming in Python.

Object-Oriented concepts: instance methods, static methods, and class methods.

The role of self vs cls in Python methods.

Input handling, error handling (e.g., division by zero), and writing CLI-based applications.

Structuring code for readability and reusability.

📂 Repository Structure
📁 PythonCalculatorProjects
 ├── PythonProgramming_PythonProject1_Calculator(CLI).ipynb
 ├── PythonProgramming_PythonProject1_Calculator(CLI)_ImplementingOOPsConcept.ipynb
 ├── PythonProgramming_PythonProject_Calculator(CLI)_ImplementingOOPsConcept_usingStaticMethod.ipynb
 ├── PythonProgramming_PythonProject_Calculator(CLI)_ImplementingOOPsConcept_usingClassMethod.ipynb
 └── Normal_vs_StaticMethods_Explanation.ipynb

▶️ Example Run (Class Method Version)
=== SIMPLE CALCULATOR ===
 Choose Operation:
 1. Addition (+)
 2. Subtraction (-)
 3. Multiplication (*)
 4. Division (/)

 Enter your Choice (+ , - , * , /) : +
 Enter your first number: 7
 Enter your second number: 3
 Result :  10.0

🔑 Key Takeaway

This repository is more than just a calculator project—it’s a step-by-step roadmap for learning Python programming. Starting with functions, moving to OOP with instance methods, then to static methods, and finally to class methods, you will develop a deep understanding of how Python handles different method types in real-world applications.
