# Churn Rate Classification

## Overview

This project aims to predict customer churn using machine learning classification techniques. By preprocessing the data, handling class imbalance, and employing multiple classification algorithms, the project demonstrates an end-to-end solution for churn prediction. Key performance metrics such as accuracy and classification reports are used to evaluate the models.

## Features

- **Data Preprocessing**:  
  - Handled missing values by removing unnecessary columns and rows with null values.
  - Performed one-hot encoding for categorical attributes.
  - Standardized feature values to improve model performance.

- **Class Imbalance Handling**:  
  - Resampled the data to address class imbalance, ensuring better model training.

- **Machine Learning Models**:  
  - **Logistic Regression**: Evaluated using accuracy and classification metrics.  
  - **Random Forest Classifier**: Applied ensemble learning for improved performance.

- **Evaluation Metrics**:  
  - **Accuracy**: Measures the overall performance of the model.  
  - **Classification Report**: Includes precision, recall, F1-score, and support for both classes.

## Workflow

1. **Data Loading and Cleaning**:  
   - Read the dataset and removed columns with excessive null values (`credit_score`, `rewards_earned`).
   - Removed irrelevant columns (`app_web_user`, `user`).

2. **Encoding**:  
   - Applied one-hot encoding to categorical attributes.

3. **Handling Class Imbalance**:  
   - Used `sklearn.utils.resample` to downsample the majority class.

4. **Feature Scaling**:  
   - Standardized features using `StandardScaler`.

5. **Model Training**:  
   - Trained Logistic Regression and Random Forest models.  
   - Evaluated models on the test set using performance metrics.

## Technologies Used

- **Languages**: Python  
- **Libraries**: Pandas, Scikit-learn  
