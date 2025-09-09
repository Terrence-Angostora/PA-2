# Assessment 2 – NumPy Operations

This Jupyter Notebook demonstrates basic operations using **NumPy**, focusing on random number generation, normalization, array reshaping, and filtering with conditions.

## Contents

### 1. Random Number Generation and Normalization
- Generates a **5×5 array** of random numbers between 0 and 1.  
- Calculates the **mean** and **standard deviation** of the numbers.  
- Normalizes the array using the formula:  

  \[
  X_{normalized} = \frac{X - \text{mean}}{\text{std}}
  \]

- Saves the normalized array to a file (`X_Normalize.npy`).

---

### 2. Squaring Numbers and Divisibility by 3
- Creates numbers from **1 to 100** and squares each one.  
- Reshapes the squared numbers into a **10×10 matrix**.  
- Checks which squared numbers are **divisible by 3**.  
- Saves the divisible numbers into `div_by_3.npy` and loads them back.

---

## Requirements
- Python 3.x  
- NumPy  

Install NumPy if not available:
```bash
pip install numpy
```

## How to Run
1. Open the notebook (`Asessment 2.ipynb`) in Jupyter Notebook or JupyterLab.  
2. Run the cells in order.  
3. The program will generate `.npy` files containing the results.  
