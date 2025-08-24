
# Student Performance Prediction

This project focuses on predicting student exam scores by leveraging various student-related and environmental factors using linear regression models.

## Project Methodology

The analysis followed a structured approach:

1.  **Data Acquisition & Initial Assessment:** The dataset was loaded, and a preliminary examination was conducted to understand its structure, identify missing values, and determine data types.
2.  **Data Preprocessing:** Missing data in 'Teacher_Quality', 'Parental_Education_Level', and 'Distance_from_Home' were imputed using the mode. Categorical features were transformed into a numerical format via Label Encoding.
3.  **Exploratory Data Analysis (EDA):** Comprehensive visualizations, including pie charts, count plots, and scatter plots, were generated to analyze feature distributions and their relationships, particularly with the target variable 'Exam_Score'.
4.  **Feature Correlation Analysis:** The linear correlation of each feature with 'Exam_Score' was computed and ranked to highlight the most influential predictors.
5.  **Predictive Modeling & Evaluation:**
    *   **Simple Linear Regression:** A model was developed using 'Attendance', identified as the feature with the highest correlation, and evaluated using Mean Squared Error (MSE) and R-squared.
    *   **Multiple Linear Regression:** A model incorporating all features (excluding the target) was trained and assessed based on MSE and R-squared.
    *   **Polynomial Regression:** A second-degree polynomial model was applied to all features and evaluated using MSE and R-squared.

## Outcomes

The project successfully implemented and evaluated three distinct linear regression models for predicting student exam scores. The performance of each model was quantified using standard regression metrics.


## Dependencies

Required libraries are listed in the `requirements.txt` file.

## Execution

To replicate the analysis, ensure dependencies are installed from `requirements.txt` and run the project notebook.
