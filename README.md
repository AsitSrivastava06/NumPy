# 🔬 Experiment 8 – NumPy Fundamentals & Array Operations

---

## 📘 Course Information

- **Course:** Python Programming Laboratory  
- **Experiment No:** 8  
- **Title:** Study and Implementation of NumPy Operations  
- **Student Name:** Asit Kumar Srivastava  

---

## 🎯 Aim

To study and implement various NumPy array operations including array creation, indexing, slicing, mathematical computations, aggregation functions, and reshaping techniques.

---

## 📖 Objectives

- Understand NumPy array structure (`ndarray`)
- Perform element-wise mathematical operations
- Apply aggregation and statistical functions
- Implement indexing and slicing techniques
- Demonstrate reshaping and transformation of arrays
- Compare efficiency of NumPy with Python lists

---

## 🧠 Theory

NumPy (Numerical Python) is a powerful open-source Python library used for numerical and scientific computing.

It provides:

- Multidimensional array object (`ndarray`)
- Vectorized mathematical operations
- Broadcasting functionality
- High-performance numerical computation
- Memory-efficient data storage

### Why NumPy is Important?

- Faster than Python lists
- Optimized for large datasets
- Foundation for:
  - Pandas
  - SciPy
  - Matplotlib
  - Machine Learning frameworks

NumPy arrays are:
- Homogeneous (same data type)
- Efficient in computation
- Designed for numerical analysis

---

## ✨ Key Concepts Implemented

- Array Creation (`np.array`, `np.zeros`, `np.ones`)
- Indexing & Slicing
- Element-wise Operations
- Aggregation Functions (`sum`, `mean`, `max`, `min`)
- Reshaping Arrays
- Vectorized Computation
- Basic Numerical Data Analysis

---

## 🛠️ Technologies Used

- Python 3
- NumPy Library
- Jupyter Notebook (Google Colab)

---

## ▶️ Usage

Open the Jupyter Notebook:

```bash
Experiment_8.ipynb
```

Run all cells sequentially to observe:

- Array creation
- Mathematical operations
- Statistical analysis
- Output results

---

## 💻 Sample Implementation

```python
import numpy as np

# Creating a NumPy array
arr = np.array([10, 20, 30, 40, 50])

# Display array
print("Array:", arr)

# Mathematical Operations
print("Sum:", np.sum(arr))
print("Mean:", np.mean(arr))
print("Maximum:", np.max(arr))
print("Minimum:", np.min(arr))

# Element-wise operation
print("Squared Values:", arr ** 2)

# Reshaping example
matrix = arr.reshape(5, 1)
print("Reshaped Matrix:\n", matrix)
```

---

## 📊 Learning Outcomes

After completing this experiment, I have:

- Gained understanding of NumPy array structure
- Performed optimized numerical computations
- Applied statistical and aggregation techniques
- Implemented vectorized operations
- Improved performance-oriented coding skills

---

## 🚀 Future Enhancements

- Matrix multiplication examples
- Random number generation using NumPy
- Performance comparison with Python lists
- Mini data analysis project
- Visualization using Matplotlib

---

## 🏁 Conclusion

This experiment successfully demonstrates the implementation of NumPy operations for efficient numerical computation. NumPy significantly improves performance and simplifies mathematical operations compared to traditional Python lists, making it essential for data science, scientific computing, and machine learning applications.

---

## 👨‍💻 Author

**Asit Kumar Srivastava**  
Electronics & Telecommunication Engineering  
Python & Data Analysis Enthusiast  

---
