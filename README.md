# Project 6: End-to-End Machine Learning Pipeline for Heart Disease Prediction

## Project Overview

This project implements an end-to-end machine learning workflow using the Heart Disease dataset. It demonstrates data understanding, preprocessing, feature engineering, model training, and evaluation using Python and Scikit-learn.

## Objectives

- Understand dataset structure, features, and target variable.
- Identify missing values, duplicates, and data inconsistencies.
- Perform appropriate preprocessing and feature engineering.
- Apply feature scaling and categorical encoding where required.
- Split data into training and testing sets.
- Train and evaluate Logistic Regression and baseline models.
- Compare training and testing performance to assess overfitting and underfitting.

## Technology Stack

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Machine Learning Workflow

1. Data loading and understanding
2. Data quality assessment
3. Data preprocessing
4. Feature engineering and scaling
5. Train-test split
6. Model training
7. Model evaluation
8. Generalization analysis
9. Final conclusions

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Training versus testing performance

## Dataset

Source: [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

The dataset is used for educational machine learning experimentation.

## Repository Structure

```text
Project-6-Heart-Disease/
├── Heart_Attack_Prediction.ipynb
├── README.md
└── heart/
    └── heart.csv
```

*Update the notebook filename and folder structure if your actual files differ.*

## Important Methodological Notes

- Fit preprocessing steps on training data only to avoid data leakage.
- Use a stratified train-test split when appropriate for classification.
- Logistic Regression is the primary classification model.
- Linear Regression is not a suitable primary classifier for a binary target; if included for educational comparison, explain its limitations.
- Outlier handling must be justified by the data and domain context.
- Report actual evaluation results rather than assumed values.

## Disclaimer

This project is for educational and research purposes only. Its predictions are not a substitute for professional medical evaluation.

## Author

Data Science | Machine Learning | AI Engineering