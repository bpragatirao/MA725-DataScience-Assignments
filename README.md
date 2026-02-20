# MA725-DataScience-Assignments
Scientific Computing Methods for Data Science: Assignments > A collection of numerical methods and computational algorithms implemented for data science. Includes solutions for linear systems, optimization, and statistical modeling.

# Scientific Computing Methods for Data Science

This repository contains a collection of assignments and implementations focusing on the numerical and algorithmic foundations of Data Science. The projects emphasize efficiency, stability, and the mathematical theory behind common computational tools.

## 🚀 Key Implementations

### 1. Matrix Decompositions
High-efficiency implementations of fundamental matrix operations used in dimensionality reduction and system solving.
* **LU Decomposition:** Solving linear systems using lower and upper triangular matrix factorization with partial pivoting.
* **QR Factorization:** Implementation via Gram-Schmidt and Householder reflections for solving least-squares problems.
* **Singular Value Decomposition (SVD):** Applications in Principal Component Analysis (PCA) and low-rank matrix approximation.

### 2. Numerical Optimization
Iterative methods for minimizing loss functions and finding roots.
* **Steepest Descent:** Implementation of gradient descent with a focus on **convergence analysis** and line-search strategies.
* **Newton’s Method:** Second-order optimization for faster convergence in well-behaved functions.
* **Conjugate Gradient:** An efficient alternative for large, sparse symmetric positive-definite systems.

### 3. Convergence & Stability Analysis
* Empirical analysis of convergence rates (Linear vs. Quadratic).
* Investigation of condition numbers and their impact on numerical stability.
* Error analysis comparing floating-point arithmetic across different algorithms.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** NumPy, SciPy (for validation), Matplotlib (for convergence plotting)
* **Environments:** Jupyter Notebooks / Python Scripts

## 📁 Structure
```text
├── LU_Decomposition/        # Doolittle/Crout algorithms
├── QR_Factorization/       # Householder & Gram-Schmidt
├── Optimization/           # Steepest Descent & Convergence plots
├── SVD_Applications/       # Image compression & PCA
└── requirements.txt        # Project dependencies
```
