### Runge-Kutta 4 Using Taylor Series
---
This repository contains a detailed mathematical derivation of the classical 4th-order Runge-Kutta (RK4) method using Taylor series expansion. The derivation process starts from first principles and proceeds by solving a system of non-linear equations by the Newton-Raphson method for solving systems of non-linear equations using both Wolfram Mathematica and Python's `sympy` library.


## 📘 Overview

The Runge-Kutta methods are widely used numerical techniques for solving ordinary differential equations (ODEs). This project focuses on deriving the RK4 method coefficients by matching terms in the Taylor series expansion, forming a nonlinear system which is then solved symbolically.

## Newton-Raphson method

The formula, \[x_k = x_{k-1} - [J(x_{k-1})]^{-1} * F(x_{k-1})\], updates the solution vector x by subtracting the inverse of the Jacobian J(x) multiplied by the function vector F(x) at the previous guess $x_{k-1}$. This process continues until the solution converges to a satisfactory level of accuracy. 

## 🧮 Key Components

- **Wolfram Mathematica Notebook**:  
  The derivation begins in a Wolfram Mathematica with step-by-step development of the RK4 method using Taylor expansion which lead to a system of non-linear equation of order 7. Then, another solves the non-linear equation gotten using Newton-Raphson method for about 25 iterations to study its convergence. 

- **System of Non-linear Equations**:  
  The Taylor series matching leads to a system of nonlinear equations that determine the RK4 coefficients.

- **Symbolic Solution using SymPy**:  
  The system is solved using the Newton-Raphson method implemented with Python’s `sympy` library, ensuring symbolic and precise computation.


## 🧑‍💻 Technologies Used

- Python libraries: SymPy, Pandas
- Wolfram Mathematica notebook 📓
- Jupyter Notebook 📓


## 📂 Repository Structure
```
Runge-Kutta-4-using-Taylor-series/
│
├── jupyter_notebook/
│  └── RK4.ipynb                  # Symbolic solver using Newton-Raphson
│
├── mathematica_notebooks/
|  ├── Newton_Raphson.nb          # Mathematica notebook for solving the non-linear equation using Newton-Raphson method 
│  └── RK4s_Derivation.nb         # Main notebook with derivation steps
│
├── README.md
└── requirements.txt
```

