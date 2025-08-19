🎓 Student Performance Prediction

This project predicts student exam scores based on academic and socio-demographic factors using different linear regression approaches.

Project Workflow
Data Loading and Exploration

Loaded the dataset and inspected structure, missing values, and data types.

Data Preprocessing

Filled missing values in Teacher_Quality, Parental_Education_Level, and Distance_from_Home using mode imputation.

Applied Label Encoding to convert categorical features into numerical format.

Exploratory Data Analysis (EDA)

Created pie charts, count plots, and scatter plots to analyze categorical distributions and feature-target relationships.

Correlation Analysis

Calculated correlations with Exam_Score.

Identified Attendance as the strongest predictor.

Model Training and Evaluation

Simple Linear Regression: Trained with Attendance as predictor.

Multiple Linear Regression: Trained with all features (except target).

Polynomial Regression (Degree 2): Trained with all features to capture non-linear patterns.

Models evaluated using Mean Squared Error (MSE) and R² score on training and test sets.

Results and Insights

Simple vs. Multiple Linear Regression: Both achieved similar R² and MSE, showing that adding weakly correlated features gave little improvement over using only Attendance.

Polynomial Regression: Outperformed linear models with higher R² and lower MSE, highlighting the presence of non-linear relationships between features and exam scores.

Key Takeaways

Attendance is the most influential linear predictor of exam performance.

Additional features with low correlation did not improve linear models.

Polynomial Regression effectively captured non-linear trends, leading to better predictive performance.
