# Bangalore House Price Prediction - Machine Learning Project

## Table of Contents
1. Introduction
2. Dataset
3. Data Preprocessing
4. Feature Engineering
5. Models Used
6. Evaluation Metrics
7. Results
8. Conclusion
9. Future Work
10. References

## 1. Introduction
This project aims to predict house prices in Bangalore using various machine learning models. It includes data preprocessing, feature engineering, training models, evaluating them, and comparing their performance to find the best model.

## 2. Dataset
We used the "Bengaluru House Price Data" from Kaggle. It contains features like area type, location, house size, total square feet, number of bathrooms, balcony count, and house price.

## 3. Data Preprocessing
Steps involved in cleaning and preparing the data:

- Handling missing values by removing columns with too many missing entries and filling others.
- Converting categorical data (like area type) to numbers using one-hot encoding.
- Scaling numeric features using Min-Max scaling.
- Removing outliers using Z-score analysis.

## 4. Feature Engineering
We created new features and refined existing ones, including:

- Converting 'total_sqft' to numeric format, dealing with ranges or text entries.
- Extracting the number of bedrooms (BHK) from the 'size' feature.
- Adding new features to help the models make better predictions.

## 5. Models Used
We tried seven regression models:

- **Linear Regression**: Assumes a straight-line relationship between features and house prices.
- **Lasso Regression**: Linear model that uses L1 regularization to avoid overfitting.
- **Ridge Regression**: Similar to Lasso but uses L2 regularization.
- **Random Forest Regression**: Uses multiple decision trees and averages their results.
- **Gradient Boosting Regression**: Builds trees sequentially, improving each time.
- **Support Vector Machine (SVM)**: Normally used for classification, adapted here for regression.
- **XGBoost**: An optimized and faster version of Gradient Boosting.

## 6. Evaluation Metrics
To evaluate the models, we used:

- **Root Mean Squared Error (RMSE)**: Measures the average error between predicted and actual prices.
- **R-squared (R²) Score**: Shows how well the features explain the house prices.

## 7. Results
Here’s how the models performed:

- **Linear Regression**: RMSE: 64.90, R²: 79.03%
- **Lasso Regression**: RMSE: 62.81, R²: 80.36%
- **Ridge Regression**: RMSE: 64.86, R²: 79.05%
- **Random Forest Regression**: RMSE: 44.20, R²: 90.27%
- **Gradient Boosting Regression**: RMSE: 46.92, R²: 89.04%
- **Support Vector Machine**: RMSE: 126.27, R²: 20.63%
- **XGBoost**: RMSE: 48.87, R²: 88.11%

## 8. Conclusion
The Random Forest Regression model performed the best, with the lowest error and highest R² score. Linear and Ridge Regression did well but were outperformed by more advanced methods. Support Vector Machine was the least accurate for this dataset.

## 9. Future Work
Future improvements could include:

- Fine-tuning model parameters to boost accuracy.
- Trying more advanced regression techniques.
- Adding new features or combining datasets.
- Using cross-validation to make models more robust.

## 10. References
- Kaggle: Bengaluru House Price Data
- Scikit-learn Documentation
- XGBoost Documentation#   b a n g l o r e H o u s e P r e d i c t i o n  
 #   b a n g l o r e H o u s e P r e d i c t  
 #   b a n g l o r e H o u s e P r e d i c t  
 #   b a n g l o r e H o u s e P r e d i c t  
 