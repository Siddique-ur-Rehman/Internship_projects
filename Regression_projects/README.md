🎓 Student Performance Prediction

This project predicts student exam scores based on academic and socio-demographic factors using different linear regression approaches.

📌 Project Workflow
1. Data Loading & Exploration

Loaded the dataset and inspected structure, missing values, and data types.

2. Data Preprocessing

Filled missing values in Teacher_Quality, Parental_Education_Level, and Distance_from_Home using mode imputation.

Applied Label Encoding to convert categorical features into numerical format.

3. Exploratory Data Analysis (EDA)

Created pie charts, count plots, and scatter plots to analyze categorical distributions and feature-target relationships.

4. Correlation Analysis

Calculated correlations with Exam_Score.

Identified Attendance as the strongest predictor.

5. Model Training & Evaluation

Simple Linear Regression: Trained with Attendance as predictor.

Multiple Linear Regression: Trained with all features (except target).

Polynomial Regression (Degree 2): Trained with all features to capture non-linear patterns.

Evaluated models using Mean Squared Error (MSE) and R² score on training and test sets.

📊 Results & Insights
Simple vs. Multiple Linear Regression

Both achieved similar R² and MSE.

Adding weakly correlated features provided little improvement over using only Attendance.

Polynomial Regression

Achieved higher R² and lower MSE compared to linear models.

Indicates presence of non-linear relationships between features and exam scores.

✅ Key Takeaways

Attendance is the most influential linear predictor of exam performance.

Extra features with low correlation did not enhance linear models.

Polynomial Regression effectively captured non-linear trends, leading to better predictive performance.
