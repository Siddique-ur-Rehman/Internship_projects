# Cover Type Prediction

This project aims to predict the cover type of a forest based on various environmental factors.

## Project Overview

The project involved the following steps:

1.  **Data Loading and Exploration:** Loaded the dataset and performed initial exploratory data analysis (EDA) to understand the data distribution, check for missing values and duplicates, and visualize key features like 'Cover_Type', 'Elevation', and 'Horizontal_Distance_To_Hydrology'.

2.  **Data Preprocessing:** Renamed initial unnamed columns for clarity.

3.  **Model Training:** Trained three classification models:
    *   Decision Tree Classifier
    *   Random Forest Classifier
    *   XGBoost Classifier

4.  **Model Evaluation:** Evaluated each model using accuracy, precision (weighted), and confusion matrices on both the training and test datasets.

5.  **Feature Importance Analysis:** Visualized the feature importance for the Random Forest and XGBoost models, including grouping the importance of one-hot encoded features like 'Soil_Type' and 'Wilderness_Area'.

## Evaluation Results

Here's a summary of the test data evaluation results for each model:

### Decision Tree Classifier

*   **Accuracy:** 0.9058
*   **Precision (weighted):** 0.9057

### Random Forest Classifier

*   **Accuracy:** 0.9558
*   **Precision (weighted):** 0.9559

### XGBoost Classifier

*   **Accuracy:** 0.9110
*   **Precision (weighted):** 0.9110

Based on the test set evaluation, the **Random Forest Classifier** achieved the highest accuracy and precision.

## Feature Importance

The feature importance analysis revealed the relative influence of different features on the models' predictions. Grouping the one-hot encoded features provided a better understanding of the overall importance of categories like Soil Type and Wilderness Area.

## Requirements

The libraries used in this project are listed in the `requirements.txt` file.

## How to Run

1.  Clone the repository.
2.  Install the required libraries using `pip install -r requirements.txt`.
3.  Run the Jupyter Notebook (`Tree_base.ipynb`).
