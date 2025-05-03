# Heart Disease Classification

This project uses the UCI Heart Disease dataset to train and evaluate several machine learning models for binary classification — predicting the presence or absence of heart disease. The notebook is designed for exploratory data analysis (EDA), preprocessing, model training, and evaluation.

## Features

- Loads data from the UCI repository using `ucimlrepo`
- Handles missing values with `SimpleImputer`
- Applies various scaling methods (StandardScaler, MinMaxScaler, etc.)
- Dimensionality reduction using PCA
- Visualization using Matplotlib, Seaborn, and Plotly
- Model training with:
  - Decision Tree
  - Random Forest
  - SGD Classifier
- Model evaluation with confusion matrix, classification report, and accuracy

## Dataset

- **Source**: [UCI Machine Learning Repository - Heart Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Accessed via**: `ucimlrepo` Python package

## Requirements

Install the necessary Python packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly ucimlrepo
