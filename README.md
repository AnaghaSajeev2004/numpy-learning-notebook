# NumPy Learning Notebook 🐍



This repository contains my hands-on practice with **NumPy (Numerical Python)**, a Python library widely used for numerical computing and data analysis.

The notebook covers NumPy fundamentals through practical code examples, helping me understand how to create, manipulate, analyze, and perform mathematical operations on arrays.

This project is part of my continuous learning journey in Python and Data Analytics.

## 🎯 Objectives

- Understand NumPy arrays and their properties.
- Learn array indexing, slicing, and reshaping.
- Practice mathematical and statistical operations.
- Explore array manipulation techniques.
- Build a strong foundation for data analysis using Python.

## 🛠️ Technologies Used

- **Python** — Programming language
- **NumPy** — Numerical computing library
- **Jupyter Notebook** — Interactive coding environment

## 📚 Topics Covered

### 1. NumPy Array Fundamentals
- Creating arrays using `np.array()`
- One-dimensional, two-dimensional, and three-dimensional arrays
- Array dimensions using `ndim`
- Array shape, size, and data types

### 2. Array Creation
- `np.zeros()`
- `np.ones()`
- `np.eye()`
- `np.full()`
- `np.arange()`
- `np.linspace()`
- Random array generation

### 3. Indexing and Slicing
- Accessing array elements
- Slicing one-dimensional and multidimensional arrays
- Boolean indexing and conditional selection
- Modifying array elements and copying arrays

### 4. Array Manipulation
- Reshaping arrays using `reshape()`
- Transposing arrays using `.T`
- Flattening arrays using `flatten()`
- Appending, inserting, and deleting elements
- Concatenating, stacking, and splitting arrays
- Finding unique elements

### 5. Mathematical Operations
- Addition, subtraction, multiplication, and division
- Square root, exponential, and logarithmic functions
- Trigonometric functions
- Rounding, floor, and ceiling operations
- Broadcasting and element-wise calculations

### 6. Statistical Functions
- Mean and weighted average
- Median and percentiles
- Minimum and maximum values
- Standard deviation and variance
- Statistical calculations along rows and columns

### 7. Sorting and Searching
- Sorting arrays using `np.sort()`
- Finding insertion positions using `np.searchsorted()`
- Counting occurrences using `np.bincount()`
- Identifying unique values and their counts

### 8. String Operations
- String concatenation and repetition
- Capitalization
- Splitting and replacing strings

## 💻 Sample Code

```python
import numpy as np

# Create a NumPy array
arr = np.array([10, 20, 30, 40, 50])

# Basic array operations
print("Array:", arr)
print("Mean:", np.mean(arr))
print("Maximum:", np.max(arr))
print("Minimum:", np.min(arr))
print("Standard Deviation:", np.std(arr))

# Reshape an array
matrix = np.arange(1, 10).reshape(3, 3)
print("3x3 Matrix:")
print(matrix)
```

## ▶️ How to Run the Notebook

1. Clone or download this repository.
2. Install Python if it is not already installed.
3. Install the required library:

   ```bash
   pip install numpy notebook
   ```

4. Open a terminal in the project folder.
5. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `NumPy_Practice.ipynb` and run the cells.

You can also upload the notebook to [Google Colab](https://colab.research.google.com/) and execute it in your browser.

## 🎓 Learning Outcomes

Through this practice, I am developing my understanding of:

- Numerical computing with NumPy
- Efficient array-based operations
- Data manipulation and transformation
- Basic statistical analysis
- Python skills for data analytics

## 🚀 Future Learning

I plan to continue improving my Python skills and apply NumPy concepts in practical data analytics projects using Pandas, Matplotlib, Seaborn, SQL, and Power BI.

## 👩‍💻 Author

**Anagha Sajeev**

Data Analyst Intern | Power Bi | Python | SQL 
---

⭐ This repository documents my learning progress in Python and numerical computing. Feedback and suggestions are welcome!
