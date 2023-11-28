# Python - Test-driven development

In this project, I started practicing test-driven development using 
and  in Python.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. Includes both Holberton-provided ones as well as the
following eight independently-developed:
  * [0-add_integer.txt](./tests/0-add_integer.txt)
  * [2-matrix_divided.txt](./tests/2-matrix_divided.txt)
  * [3-say_my_name.txt](./tests/3-say_my_name.txt)
  * [4-print_square.txt](./tests/4-print_square.txt)
  * [5-text_indentation.txt](./tests/text_indentation.txt)
  * [6-max_integer_test.py](./tests/6-max_integer_test.py)
  * [100-matrix_mul.txt](./tests/100-matrix_mul.txt)
  * [101-lazy_matrix_mul.txt](./tests/101-lazy_matrix_mul.txt)

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                     | Prototype                                    |
| ------------------------ | -------------------------------------------- |
|        |                   |
|     |            |
|        |  |
|       |                     |
|   |                 |
|       |                   |
|  |              |
|            |      |

## Tasks :page_with_curl:

* **0. Integers addition**
  * [0-add_integer.py](./0-add_integer.py): Python function that returns the integer addition
  of two numbers.
  * If either of  or  is not an  or , a  is raised
  with the message  or .
  * If either of  or  is a , it is casted to an 
  before addition.

* **1. Divide a matrix**
  * [2-matrix_divided.py](./2-matrix_divided.py): Python function that divides all
  elements of a matrix by a common divisor.
  * Returns a new matrix representing the division of all elements of 
  by .
  * Quotients are rounded to two decimal places.
  * If  is not a list of lists of s or s, a 
  is raised with the message .
  * If  contains rows of different lengths, a  is raised
  with the message .
  * If the divisor  is not an  or , a  is raised
  with the message .
  * If  is , a  is raised with the message
  .

* **2. Say my name**
  * [3-say_my_name.py](./3-say_my_name.py): Python function that prints a name in
  the format .
  * If either of  or  is not a , a  is
  raised with the message  or .

* **3. Print square**
  * [4-print_square.py](./4-print_square.py): Python function that prints a square using
  the  character.
  * The paramter  represents the height/width of the square.
  * If  is not an , a  is raised  with the message,
  .
  * If  is less than , a  is raised with the message .

* **4. Text indentation**
  * [5-text_indentation.py](./5-text_indentation.py): Python function that prints text with
  indentation.
  * Two new lines are printed after any , , or  character.
  * If  is not a , a  is raised with the message .
  * No spaces are printed at the beginning or end of each printed line.

* **5. Max integer - Unittest**
  * [tests/6-max_integer_test.py](./tests/6-max_integer_text.py): Python class/script
  that runs unittests for the function 
  (provided by Holberton School).

* **6. Matrix multiplication**
  * [100-matrix_mul.py](./100-matrix_mul.py): Python function that multiplies two matrices.
  * Returns a new matrix representing the multiplication of  by .
  * If either of  or  is empty (ie.  or ), a
   is raised with the message  or .
  * If either of  or  is not a list, a  is raised with
  the message  or  must be a list.
  * If either of  or  is not a list of lists, a  is raised
  with the message  or .
  * If either of  or  is not a list of lists of s or s, a
   is raised with the message  or .
  * If either of  or  contains rows of different lengths, a 
  is raised with the message  or
  .
  * If  and  cannot be multiplied (ie. row size of  does not match
  column size of ), a  is raised with the message .

* **7. Lazy matrix multiplication**
  * [101-lazy_matrix_mul.py](./101-lazy_matrix_mul.py): Python function that multiplies
  two matrices using the module .
  * Identical in function to [100-matrix_mul.py](./100-matrix_mul.py).

* **8. CPython #3: Python Strings**
  * [102-python.c](./102-python.c): C function that prints basic information about Python
  string objects.
