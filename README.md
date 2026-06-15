# NumPy Basic Learning Repository

## Overview
This repository contains comprehensive Jupyter notebooks for learning **NumPy** (Numerical Python), a powerful open-source Python library used extensively in science, engineering, and data science applications.

## What is NumPy?
NumPy is an open source Python library that provides:
- **Multidimensional array data structures** - Homogeneous, N-dimensional ndarray objects
- **Large library of mathematical functions** - For efficient operations on arrays and matrices
- **High-performance computing capabilities** - Optimized for numerical operations

## Why Use NumPy?

While Python lists are versatile and general-purpose, NumPy excels when you need to:

- ✅ Work with **large quantities of homogeneous data** (same data type)
- ✅ Perform **fast numerical computations** (much faster than Python lists)
- ✅ **Reduce memory consumption** with efficient array storage
- ✅ Leverage **high-level syntax** for complex mathematical operations
- ✅ Integrate seamlessly with **scientific and data science libraries** (pandas, scikit-learn, matplotlib, etc.)

## Installation

Install NumPy using pip:

```bash
pip install numpy
```

## Contents

### 📓 01_numpay.ipynb
**Fundamental NumPy Concepts**

This notebook covers the basics of NumPy including:
- What is NumPy and its purpose
- Why NumPy is preferred over Python lists
- Installation instructions
- Importing NumPy
- Understanding NumPy arrays
- Creating and manipulating arrays
- Array indexing and slicing
- Basic array operations

### 📓 02_numpay.ipynb
**Advanced Array Operations**

This notebook explores:
- Creating arrays from existing arrays
- Using `np.arange()` for generating number sequences
- Array manipulation and reshaping
- Working with array dimensions
- Advanced array operations and functions
- Practical examples and use cases

## Quick Start

### Importing NumPy

```python
import numpy as np
```

### Creating Arrays

```python
# From a Python list
arr = np.array([1, 2, 3, 4, 5])

# Using arange to create a sequence
arr = np.arange(0, 50, 2)  # Creates array from 0 to 50 with step 2

# Using zeros or ones
zeros = np.zeros((3, 3))
ones = np.ones((2, 4))
```

### Basic Operations

```python
# Element-wise operations
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
c = a + b  # [5, 7, 9]

# Array properties
print(a.shape)    # Dimensions
print(a.dtype)    # Data type
print(a.size)     # Total elements
```

## Prerequisites

- Python 3.6 or higher
- Basic understanding of Python programming
- Jupyter Notebook or Jupyter Lab installed

## Getting Started

1. Clone or download this repository
2. Install NumPy:
   ```bash
   pip install numpy
   ```
3. Open the notebooks with Jupyter:
   ```bash
   jupyter notebook
   ```
4. Start with `01_numpay.ipynb` and progress to `02_numpay.ipynb`

## Key Topics Covered

- ✓ NumPy fundamentals and core concepts
- ✓ Array creation and initialization
- ✓ Array indexing and slicing
- ✓ Array operations and transformations
- ✓ Working with multi-dimensional arrays
- ✓ Practical examples and use cases

## Resources & References

- [Official NumPy Documentation](https://numpy.org/doc/)
- [NumPy Tutorial](https://numpy.org/doc/stable/user/tutorials_index.html)
- [NumPy Reference Guide](https://numpy.org/doc/stable/reference/)

## Target Audience

- Beginners learning numerical computing in Python
- Data science students starting their journey
- Anyone wanting to strengthen their NumPy skills
- Developers transitioning from basic Python to scientific computing

## License

This learning repository is provided for educational purposes.

---

**Happy Learning with NumPy!** 🐍📊✨
