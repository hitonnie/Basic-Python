Basic Python

A collection of small, standalone Python scripts from FNB Week 7, each demonstrating a core Python concept: variables, operators, strings, numeric types, control flow, and loops. This is the first project in the series to move away from HTML/JS and into a general-purpose scripting language.

Scripts
File	Concept	Description
Variables.py	Variable declaration & naming rules	Demonstrates valid variable names, plus commented examples of invalid naming
Operators.py	Numeric operators	Addition, subtraction, multiplication, division, modulus, and exponentiation
Operators2.py	String operators	String concatenation with + and repetition with *
Strings.py	String basics	Declaring and printing a triple-quoted string
#Strings2.py	String methods	.strip(), .lower(), and .split() on a string
NumericData.py	Numeric types	Using type() to inspect int vs float values
Control.py	Conditionals	if / elif / else to classify a number as positive, zero, or negative
Control2.py	Conditionals with input	Reads two numbers via input() and compares them
Loops.py	while loops	Counts from 1 to 5
Loops2.py	Loop control (break)	Counts up and exits early once a condition is met
Project Structure
Basic-Python/
├── Variables.py
├── Operators.py
├── Operators2.py
├── Strings.py
├── #Strings2.py
├── NumericData.py
├── Control.py
├── Control2.py
├── Loops.py
├── Loops2.py
└── README.md
How to Run

Requires Python 3 installed locally.

Clone the repository:
bash
   git clone https://github.com/hitonnie/Basic-Python.git
Run any script directly:
bash
   python3 Variables.py

(Control2.py will prompt for input in the terminal.)

Built With
Python 3 (standard library only, no external dependencies)
Known Issues
#Strings2.py has a literal # in its filename. This likely happened by accident (the # was probably meant as a comment inside the file, not part of the filename) and can cause issues on some systems/shells where # has special meaning. Consider renaming it to Strings2.py.
Context

Built as part of Week 7 coursework, this project introduces Python fundamentals as a set of isolated exercises, mirroring the approach used in the earlier Basic JavaScript project.
