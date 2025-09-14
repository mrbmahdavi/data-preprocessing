# data-preprocessing
Data Preprocessing Techniques for Machine Learning

# Data Preprocessing Template

This repository contains a Jupyter Notebook demonstrating essential data preprocessing techniques for machine learning, based on the Machine Learning A-Z course.

## Overview

The notebook covers the complete data preprocessing pipeline including:
- Handling missing data
- Encoding categorical variables
- Feature scaling
- Train-test splitting

## Key Techniques Implemented

### 1. Handling Missing Data
- Used `SimpleImputer` from scikit-learn to replace missing values with column means
- Applied to both numerical features (Age and Salary columns)

### 2. Encoding Categorical Data
- Implemented One-Hot Encoding for categorical variables (Country column)
- Used `ColumnTransformer` and `OneHotEncoder` from scikit-learn
- Applied Label Encoding for the target variable (Purchased column)

### 3. Feature Scaling
- Standardized numerical features using `StandardScaler`
- Applied scaling after train-test split to prevent data leakage
- Excluded dummy variables from scaling

### 4. Train-Test Splitting
- Used `train_test_split` from scikit-learn
- 80-20 split ratio (8 training samples, 2 test samples)

## Dataset

The preprocessing is performed on a sample dataset (`Data.csv`) containing:
- Country: Categorical feature (France, Spain, Germany)
- Age: Numerical feature (with some missing values)
- Salary: Numerical feature (with some missing values)
- Purchased: Target variable (Yes/No)

## Requirements

- Python 3.x
- NumPy
- pandas
- scikit-learn
- matplotlib

## Usage

1. Clone the repository
2. Ensure you have the required libraries installed
3. Run the Jupyter Notebook `Jozve preprocessing.ipynb`
4. The notebook will guide you through each preprocessing step with explanations

## Note

This template serves as a foundation for data preprocessing in machine learning projects. The techniques demonstrated here are essential for preparing raw data for various machine learning algorithms.
