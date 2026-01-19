# Return Prediction with LASSO and Neural Networks

This repository contains a Jupyter Notebook implementing machine learning models for **predicting asset returns** using firm-level characteristics and macroeconomic variables.

The work was completed as part of a coursework assignment and focuses on comparing linear and non-linear models in a panel-data setting.

## Models Implemented
- **LASSO regression**
- **Feedforward Neural Networks** with varying depth (NN2, NN3, NN4)
- Regularization via L1 penalties, dropout, and batch normalization
- Early stopping for overfitting control

## Data
The analysis uses pre-processed pickle files:
- `returns_chars_panel.pkl` – firm-level returns and characteristics
- `macro_timeseries.pkl` – macroeconomic time series

> Returns are assumed to be pre-shifted to avoid look-ahead bias.

## Methodology
1. Data loading and train/validation split
2. Hyperparameter tuning for neural networks
3. Out-of-sample return prediction
4. Model evaluation using MSE and \(R^2\)

## Requirements
- Python 3.x
- TensorFlow / Keras
- scikit-learn
- pandas, numpy

## Notes
- The code is written as a single notebook for clarity and instructional purposes.
- Results are intended for academic evaluation rather than production deployment.

## Author
Krzysztof Płachta
