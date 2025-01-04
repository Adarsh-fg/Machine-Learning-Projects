# Loan Prediction: EDA and Classification

This repository contains an exploratory data analysis (EDA) and classification model development for predicting loan statuses. The project is aimed at understanding the dataset, handling imbalanced data, and building accurate predictive models.

## Dataset

The dataset used in this project can be found [here](https://drive.google.com/file/d/1vlK7fnZeyDhQunpLipNpj7TqnlBiM9M2/view?usp=drive_link).

### Features Description

- **Independent Features:**
  - Loan ID
  - Loan Percent Income
  - Loan Interest Rate
  - Person's Home Ownership
  - Previous Loan Defaults, etc.

- **Target Variable:**
  - Loan Status

## Project Overview

### Problem Statement
Loan defaults are a growing challenge for financial institutions, leading to significant losses. This project aims to develop a model that predicts loan defaults using EDA and machine learning techniques.

### Steps Followed
1. **Data Exploration:**
   - Basic information about the dataset (shape, columns, data types, missing values, descriptive statistics).
   - Visualizations for understanding distributions and patterns.

2. **Data Cleaning:**
   - Addressing missing values and encoding categorical features using `LabelEncoder`.
   - Removing skewness and normalizing distributions.

3. **Data Balancing:**
   - Using techniques like SMOTE to handle imbalanced datasets.

4. **Feature Selection:**
   - Analyzing correlations and selecting features with significant relationships to the target variable.

5. **Model Development:**
   - Logistic Regression, Random Forest, and other models.
   - Data scaling and dimensionality reduction with PCA.
   - Hyperparameter tuning for optimized performance.

### Key Results
- **Random Forest Accuracy:** 88.39%
- PCA-based dimensionality reduction improved model efficiency.
- Challenges with outliers were addressed but negatively impacted model accuracy.

## Requirements

To reproduce the results, install the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

You can install these packages using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Loan Prediction EDA Classification.ipynb"
   ```

3. Follow the steps outlined in the notebook to explore the data and train models.

## Conclusion

This project demonstrates the end-to-end pipeline for handling imbalanced datasets, performing EDA, and training machine learning models to predict loan statuses. It highlights the importance of data preprocessing and feature engineering in achieving high accuracy.
