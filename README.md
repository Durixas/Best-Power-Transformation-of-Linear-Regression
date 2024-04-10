# Best-Power-Transformation-of-Linear-Regression
This repository contains PyTorch code to compute the optimal power transformation exponent for linear regression. The goal is to find the best transformation exponent \( $\lambda$ \) by minimizing the sum of squares (SS) of residuals using PyTorch's optimization capabilities. Additionally, it compares different models including the initial model, the optimized model with the best \( $\lambda$ \), and a model using a square root transformation.

## Key Features

- **Power Transformation:** Seek the best transformation exponent \( $\lambda$ \) that minimizes the model's residual sum of squares.
  
- **Optimization Process:** Implement the minimization of the residual sum of squares using PyTorch's optimization capabilities.
  
- **Model Comparison:** Compare different models:
  - **Initial Model:** The original linear regression model.
  - **Optimized Model:** The model with the optimal transformation exponent \( $\lambda$ \).
  - **Square Root Transformation Model:** A model using a square root transformation for comparison purposes.
