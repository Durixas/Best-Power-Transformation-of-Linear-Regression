# Best-Power-Transformation-of-Linear-Regression
This repository contains PyTorch code to compute the optimal power transformation exponent for linear regression. The goal is to find the best transformation exponents by minimizing the model's sum of squares (SS) of residuals using PyTorch's optimization capabilities. Additionally, it compares different models including the initial model, the optimized models with the best exponents, and models using square root transformation.

## Key Features

- **Power Transformation:** Seek the best transformation exponents that minimize the model's residual sum of squares.
  
- **Optimization Process:** Implement the minimization of the residual sum of squares using PyTorch's optimization capabilities.
  
- **Model Comparison:** Compare different models:
  - **Initial Model:** The original linear regression model.
  - **Optimized Model (one side):** The model with the optimal transformation exponent \( $\lambda$ \) on $Y$.
  - **Square Root Model (one side):** A model using square root transformation on $Y$ for comparison purposes.
  - **Optimized Model (two sides):** The model with the optimal transformation exponent \( $p$, $q$ \) on $X$ and $Y$.
  - **Square Root Model (two sides):** A model using square root transformation on $X$ and $Y$ for comparison purposes.
