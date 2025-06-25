# Regularization
- Regularization in Machine Learning is a technique used to prevent overfitting by adding a penalty term to the model's loss function. This penalty discourages the model from becoming too complex and helps it generalize better to unseen data.
## Why Regularization?
- When a model learns too much from training data, including noise, it performs poorly on new data — this is called overfitting.

Regularization helps by:

- Keeping model weights smaller.

- Simplifying the model.

- Making it more robust and general.
# Types of Regularization
## 1. L1 Regularization (Lasso)
- Adds the absolute value of weights to the loss function.

- Encourages sparsity (some weights become exactly 0).

- Useful for feature selection.

- **Loss = MSE + λ × Σ|weights|**

## 2. L2 Regularization (Ridge)
- Adds the squared value of weights to the loss function.

- Encourages smaller, but non-zero weights.

- Keeps all features but with less influence.

- **Loss = MSE + λ × Σ(weights/m²)**

## 3. Elastic Net
- Combines both L1 and L2.

- Useful when there are many correlated features.

