# **Python - Test-driven development**

In this project, I started practicing test-driven development using docstring and unittest in Python.


# Tests 
* **tests:** Folder of test files. Includes both Holberton-provided ones as well as the following eight independently-developed:
  * 0-add_integer.txt
  * 2-matrix_divided.txt
  * 3-say_my_name.txt
  * 4-print_square.txt
  * 5-text_indentation.txt
  * 6-max_integer_test.py
  * 100-matrix_mul.txt
  * 101-lazy_matrix_mul.txt

# Function Prototypes 
Prototypes for functions written in this project:

| **File**	| **Prototype** |
| --- | --- |
| 0-add_integer.py	| def add_integer(a, b=98): |
| 2-matrix_divided.py	| def matrix_divided(matrix, div): |
| 3-say_my_name.py	| def say_my_name(first_name, last_name=""): |
| 4-print_square.py	| def print_square(size): |
| 5-text_indentation.py	| def text_indentation(text): |
| 100-matrix_mul.py	| def matrix_mul(m_a, m_b): |
| 101-lazy_matrix_mul.py	| def lazy_matrix_mul(m_a, m_b):C
| 102-python.c	| void print_python_string(PyObject *p); |


# Tasks 

* ### 0. Integers addition

        * 0-add_integer.py: Python function that returns the integer addition of two numbers.
        * If either of a or b is not an int or float, a TypeError is raised with the message a must be an integer or b must be an integer.
        * If either of a or b is a float, it is casted to an int before addition.

 * **1. Divide a matrix**
        * 2-matrix_divided.py: Python function that divides all elements of a matrix by a common divisor.
        * Returns a new matrix representing the division of all elements of matrix by div.
        * Quotients are rounded to two decimal places.
        * If matrix is not a list of lists of ints or floats, a TypeError is raised with the message matrix must be a matrix (list of lists) of integers/floats.
        * If matrix contains rows of different lengths, a TypeError is raised with the message Each row of the matrix must have the same size.
        * If the divisor div is not an int or float, a TypeError is raised with the message div must be a number.
        * If div is 0, a ZeroDivisionError is raised with the message division by zero.
