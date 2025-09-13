# CS5710-Home-Assignment

# Linear Regression — Closed-Form vs Gradient Descent (from scratch)

This project implements simple linear regression two ways on a **synthetic** dataset:

1. **Closed-form (Normal Equation)**  
   \[
   \theta = (X^\top X)^{-1} X^\top y
   \]
2. **Gradient Descent (GD)** with mean-squared-error (MSE) loss  
   Update rule:
   \[
   \theta \leftarrow \theta - \eta \cdot \frac{2}{m} X^\top(X\theta - y)
   \]

It then compares the fitted lines and shows the GD **loss vs. iterations** curve.

---

## Files

- `your_script.py` — the Python code you pasted (contains data gen, closed-form, GD, and plots).

> If you rename the file, update the command below accordingly.

---

## Requirements

- Python 3.8+  
- Packages:
  ```bash
  pip install numpy matplotlib

