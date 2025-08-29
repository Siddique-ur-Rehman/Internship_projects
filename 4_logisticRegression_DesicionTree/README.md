# Loan Approval Prediction Project

## Overview

This project focuses on building and evaluating classification models to predict loan approval status. Leveraging a dataset containing various financial and personal attributes of loan applicants, we explore data analysis, preprocessing, and model training using Logistic Regression and Decision Trees.

## Dataset

The analysis is based on the `loan_approval_dataset.csv` file. This dataset includes key features such as income, assets, education level, self-employment status, and the final loan status (Approved or Rejected).

## Methodology

The project follows a standard machine learning workflow:
1.  **Data Loading and Exploration**: Initial understanding of the dataset.
2.  **Data Preprocessing**: Handling categorical features and preparing data for modeling.
3.  **Model Training**: Implementing and training Logistic Regression and Decision Tree classifiers.
4.  **Evaluation**: Assessing model performance.

## Results

The models were evaluated based on accuracy.

-   **Logistic Regression Accuracy**:
    -   Train Data: 0.795
    -   Test Data: 0.796
-   **Decision Tree Accuracy**:
    -   Train Data: 1.000
    -   Test Data: 0.972

The Decision Tree model shows significantly higher accuracy on both the training and test sets, indicating better performance on this dataset.
