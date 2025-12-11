# Logistic Regression Tutorial — Social Network Ads Dataset

This repository contains a Jupyter Notebook demonstrating the implementation of a **Logistic Regression** model for binary classification sing the Social Network Ads dataset from Kaggle ([Social Network Ads on Kaggle](https://www.kaggle.com/datasets/rakeshrau/social-network-ads)

## Overview
The notebook walks through:
1. Importing and preprocessing data
2. Training a Logistic Regression model
3. Evaluating model performance
4. Visualizing decision boundaries and ROC curve

The ROC-AUC shows excellent discrimination between classes, and all visualizations use colorblind-safe colormaps for accessibility.

- Features: Gender, Age, Estimated Salary
- Target: Purchased (0 = No, 1 = Yes)

## Requirements
- Jupyter Lab
- pandas, numpy, matplotlib, scikit-learn

## Running the Notebook
1. Clone this repository  
2. Open `Logistic_Regression_Tutorial.ipynb` in JupyterLab  
3. Run all cells (`Kernel → Restart & Run All`)

## Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 0.89  |
| Precision | 0.91  |
| Recall    | 0.75  |
| F1-score  | 0.82  |
| AUC       | 0.97  |

The model achieved high accuracy and a clear separation between classes based on Age and Salary.  
The ROC curve shows good discrimination capability with AUC > 0.95.
