### Runge-Kutta 4 Using Taylor Series

This repository contains a detailed mathematical derivation of the classical 4th-order Runge-Kutta (RK4) method using Taylor series expansion. The derivation process starts from first principles and proceeds by solving a system of nonlinear equations using Python's `sympy` library and the Newton-Raphson method.

## 📘 Overview

The Runge-Kutta methods are widely used numerical techniques for solving ordinary differential equations (ODEs). This project focuses on deriving the RK4 method coefficients by matching terms in the Taylor series expansion, forming a nonlinear system which is then solved symbolically.

## 🧮 Key Components

- **Wolfram Mathematica Notebook**:  
  The derivation begins in a Wolfram Mathematica with step-by-step development of the RK4 method using Taylor expansion which lead to a system of non-linear equation of order 7.

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
├── notebooks/
│ └── RK4s_Derivation.nb # Main notebook with derivation steps
│
├── Jupyter notebook/
│ └── newton_raphson_solver.ipynb # Symbolic solver using Newton-Raphson
│
├── README.md
└── requirements.txt
```

---
✍️ Author
Shoyombo Moshood Olanrewaju
Mathematician | Python Developer | Research Enthusiast

