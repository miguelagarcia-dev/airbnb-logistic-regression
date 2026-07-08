# Logistic Regression: Model Evaluation & Selection

Trains and evaluates a logistic regression model as part of the ML life cycle's evaluation and deployment phases.

## Overview
- Train a baseline logistic regression model using the default `C` hyperparameter.
- Perform model selection (hyperparameter tuning) to find the optimal `C`.
- Compare default vs. tuned models using:
  - Confusion matrices
  - Precision-recall curves
  - ROC curves and AUC
- Perform feature selection using a built-in scikit-learn method and analyze results.
- Save the best-performing model with `pickle`.

## Files
- `model.pkl` — saved best-performing model

## Tools
Python, scikit-learn, pickle
