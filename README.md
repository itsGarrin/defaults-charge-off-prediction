# Defaults and Charge-Off Prediction

This repository focuses on predicting credit card defaults and charge-offs using machine learning. The project evaluates multiple classification models to address challenges of imbalanced datasets and identifies significant features influencing defaults.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methods](#methods)
4. [Results](#results)
5. [Dependencies](#dependencies)
6. [How to Run](#how-to-run)
7. [Contributing](#contributing)
8. [License](#license)

---

## Introduction

Credit card charge-offs are significant risks in lending. Predicting defaults effectively can help financial institutions mitigate these risks. This project uses multiple machine learning models to classify credit card accounts as likely to default and provides insights into key influencing features.

---

## Dataset

The dataset contains:
- Demographic and financial features.
- Binary target variable indicating default or charge-off status.

The dataset is imbalanced, with a minority class representing defaults.

---

## Methods

### Data Preprocessing
- Imputation for missing values.
- Scaling and encoding categorical variables.

### Modeling
The following models were used to predict defaults:
1. ANN  
2. Random Forest  
3. Gradient Boosting (XGBoost)  
4. AdaBoost  

### Model Evaluation
- Metrics: Accuracy, precision, recall, F1-score, and AUC-ROC.
- Focus on improving recall for the minority (default) class.

---

## Results

Key insights include:
- Important features contributing to defaults.
- Performance comparisons across models, highlighting the trade-offs in precision and recall.

---

## Dependencies

- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- XGBoost
