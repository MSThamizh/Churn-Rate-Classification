# Churn Rate Classification

This project aims to predict customer churn using machine learning classification techniques. By classifying whether a customer is likely to churn or not, businesses can take proactive measures to retain their customers. The project utilizes historical customer data and various features like demographics, usage patterns, and customer interaction metrics.

## Problem Statement

The goal of this project is to build a machine learning model that predicts whether a customer will churn (leave the service) based on various customer features. Churn prediction is essential for businesses to identify at-risk customers and reduce churn rates by offering targeted interventions.

## Workflow

1. **Data Collection**: The dataset contains historical customer data, including demographic details, service usage, and interaction history.
2. **Data Preprocessing**:
   - Handle missing values using mean/median imputation.
   - Encode categorical variables using techniques like one-hot encoding or label encoding.
   - Normalize continuous features for better model performance.
3. **Feature Engineering**:
   - Create new features (if applicable) to enhance model prediction.
   - Remove highly correlated features to prevent multicollinearity.
4. **Model Training**:
   - Train multiple classification models such as **Logistic Regression**, **Random Forest**, **Support Vector Machines (SVM)**, and **Gradient Boosting**.
   - Apply hyperparameter tuning to optimize model performance.
5. **Model Evaluation**:
   - Evaluate models using classification metrics such as **Accuracy**, **Precision**, **Recall**, and **F1-Score**.
6. **Prediction**:
   - The model predicts the likelihood of customer churn based on input features.

## Features

- **Data Preprocessing**: 
  - Fill missing values with statistical methods (mean, median).
  - Encode categorical variables for machine learning models.
  - Standardize continuous features to improve model performance.
  
- **Model Training & Evaluation**:
  - Multiple machine learning classifiers trained and compared.
  - Hyperparameter optimization via grid search or random search.
  
- **Prediction**: 
  - The model predicts whether a customer will churn based on their features.
  
## Technologies Used

- **Python**: Main programming language for data processing and machine learning model development.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Pandas**: For data manipulation and cleaning.

## Results

### Model Performance:

| Model                     | Accuracy       | Precision (0) | Recall (0) | F1-Score (0) | Precision (1) | Recall (1) | F1-Score (1) | F1-Score (Macro Avg) |
|---------------------------|----------------|---------------|------------|--------------|---------------|------------|--------------|----------------------|
| **Logistic Regression**    | 0.65           | 0.68          | 0.76       | 0.72         | 0.59          | 0.48       | 0.53         | 0.62                 |
| **Random Forest Classifier**| 0.70           | 0.73          | 0.79       | 0.76         | 0.66          | 0.58       | 0.62         | 0.69                 |

The **Random Forest Classifier** outperformed the **Logistic Regression** model with a higher accuracy and better F1-scores for both classes. However, both models showed good performance, with Random Forest being more effective at predicting churn.

## References

- **Python**: [https://docs.python.org/3/](https://docs.python.org/3/)
- **Scikit-learn Documentation**: [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)
