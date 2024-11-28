
# Machine Learning with NumPy - Colab Notebook

![Python](https://img.shields.io/badge/Python-3.x-blue) ![NumPy](https://img.shields.io/badge/Library-NumPy-brightgreen)

This Jupyter Notebook introduces the **NumPy** library, a fundamental package for scientific computing in Python. The notebook provides detailed explanations and hands-on code examples to illustrate the functionality of NumPy, making it an excellent resource for those new to numerical computing and machine learning.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)

## About

This notebook covers the essential concepts of **NumPy**, focusing on:
- Understanding and working with NumPy arrays.
- Performing mathematical operations like matrix manipulation, array reshaping, and statistical analysis.
- Learning about the efficiency of NumPy compared to Python’s native data structures such as lists.

This notebook is perfect for students, data scientists, and anyone looking to get started with NumPy for machine learning or data analysis.

## Features

The notebook includes:
- **NumPy Basics**: Overview of NumPy and how it enhances numerical computing in Python.
- **Array Creation**: Demonstrates how to create arrays with `np.array`, `np.arange`, and `reshape`.
- **Mathematical Operations**: Practical examples of element-wise operations, array reshaping, and linear algebra functions.
- **Comparisons**: Detailed comparison between NumPy arrays and Python sequences (lists and tuples).
- **Statistical Functions**: Illustrates NumPy’s built-in functions like `mean`, `variance`, and `standard deviation`.

## Installation

To run this notebook, you need to have Python and Jupyter installed. You can also run it directly on **Google Colab**.

### Running Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/MRH-66/Machine-Learning-101.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Machine-Learning-101
   ```
3. Install the required dependencies:
   ```bash
   pip install numpy
   ```
4. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### Running on Google Colab
You can open this notebook directly on **Google Colab** without any local installation by clicking the link below:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MRH-66/Machine-Learning-101/blob/main/Machine-Learning-(Numpy).ipynb)

## Usage

Once the notebook is open, you can explore the following:
- Run code cells to see the output of NumPy operations.
- Modify the examples to experiment with different array sizes, shapes, and mathematical operations.
- Use the provided examples to familiarize yourself with NumPy's features.

### Key Sections:
- **Creating Arrays**: Learn how to create and manipulate arrays with `np.array` and `np.arange`.
- **Mathematical Operations**: Perform operations like addition, multiplication, and matrix reshaping.
- **Statistical Functions**: Explore NumPy’s in-built functions for statistical analysis.

## Examples

### Array Creation
```python
import numpy as np
# Create a 1D array of floats
arr = np.array([1, 2, 3], dtype=float)
print(arr)
```

### Reshaping Arrays
```python
# Create a range of values and reshape into 2D
reshaped_array = np.arange(16).reshape(8, 2)
print(reshaped_array)
```

### Mathematical Operations
```python
# Element-wise addition
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
result = a + b
print(result)
```


## License

Distributed under the MIT License. See `LICENSE` for more information.
