This project focuses on predicting student exam scores based on various academic and socio-demographic factors using different linear regression approaches.

📌 Project Workflow

Data Loading & Exploration:

Imported the dataset and performed initial inspection for structure, missing values, and data types.

Data Preprocessing:

Handled missing values in Teacher_Quality, Parental_Education_Level, and Distance_from_Home using mode imputation.

Applied Label Encoding to convert categorical features into numerical form.

Exploratory Data Analysis (EDA):

Generated pie charts, count plots, and scatter plots to visualize categorical distributions and feature-target relationships.

Correlation Analysis:

Computed correlations with Exam_Score and identified Attendance as the strongest predictor.

Model Training & Evaluation:

Simple Linear Regression: Trained with Attendance as predictor (highest correlation).

Multiple Linear Regression: Trained using all features except the target variable.

Polynomial Regression (degree 2): Trained with all features to capture potential non-linear patterns.

Evaluation Metrics: Mean Squared Error (MSE) and R² score on both training and test sets.

📊 Results & Insights

Simple vs. Multiple Linear Regression:
Both models yielded similar R² and MSE, suggesting that most additional features contributed little predictive power compared to Attendance.

Polynomial Regression:
Outperformed linear models with higher R² and lower MSE, indicating that non-linear relationships exist between features and exam scores.

✅ Key Takeaways

Attendance is the most significant linear predictor of exam performance.

Adding weakly correlated features did not improve linear models.

Polynomial regression better captured feature interactions and non-linear trends, improving overall predictive accuracy.
