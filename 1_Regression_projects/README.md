# Student Performance Prediction

This project aims to predict student exam scores based on various factors using different linear regression models.

## Project Steps

1.  **Data Loading and Exploration:** The dataset containing student performance factors was loaded and initial exploration was performed to understand the data structure, check for missing values, and identify data types.
2.  **Data Preprocessing:** Missing values in the 'Teacher_Quality', 'Parental_Education_Level', and 'Distance_from_Home' columns were filled with the mode of each respective column. Categorical features were encoded using Label Encoding to convert them into numerical format for model training.
3.  **Exploratory Data Analysis (EDA):** Visualizations such as pie charts, count plots, and scatter plots were generated to analyze the distribution of categorical features and the relationship between numerical features and the target variable ('Exam_Score').
4.  **Correlation Analysis:** The correlation of each feature with the 'Exam_Score' was calculated and sorted to identify features with stronger linear relationships.
5.  **Model Training and Evaluation:**
    *   **Simple Linear Regression:** A simple linear regression model was trained using 'Attendance' as the predictor, as it showed the highest correlation with 'Exam_Score'. The model was evaluated using Mean Squared Error (MSE) and R-squared score on both the training and testing sets.
    *   **Multiple Linear Regression:** A multiple linear regression model was trained using all features except 'Exam_Score'. The model was evaluated using MSE and R-squared score.
    *   **Polynomial Regression:** A polynomial regression model with degree 2 was trained using all features. The model was evaluated using MSE and R-squared score.

## Results and Analysis

The simple linear regression model using 'Attendance' and the multiple linear regression model using all features yielded similar R-squared and MSE values. This suggests that despite including multiple features, many of the additional features had low linear correlation with the 'Exam_Score', as indicated by the correlation analysis. Therefore, adding them to a linear model did not significantly improve the predictive performance over using just the most correlated feature.

The polynomial regression model showed improved performance with a higher R-squared score and lower MSE on both the training and test sets compared to the simple and multiple linear regression models. This suggests that there might be non-linear relationships between the features and the exam score, which the polynomial model was able to capture.
