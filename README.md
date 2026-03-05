# DocGenie - Python Docstring Generator

## Project Description
DocGenie is a simple Python project that automatically generates docstrings for Python functions. It analyzes the function structure using Python's AST (Abstract Syntax Tree) and generates documentation in a standard format.

## Features
- Automatic docstring generation
- Simple and interactive user interface
- Supports Python function documentation
- Built using Gradio for web interface

## Technologies Used
- Python
- AST (Abstract Syntax Tree)
- Gradio
- Google Colab

## How It Works
1. User enters a Python function.
2. The system analyzes the function structure.
3. It extracts the function name and parameters.
4. Automatically generates a docstring.
5. Displays the documented code as output.


## Example

**Input**

```python
def add(a, b):
    return a + b
```

**Output**

```python
def add(a, b):
    """
    Adds two numbers.

    Args:
        a (int): First number
        b (int): Second number

    Returns:
        int: Sum of a and b
    """
    return a + b
```
