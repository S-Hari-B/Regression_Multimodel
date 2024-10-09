# California Housing Price Prediction

## Overview
This project demonstrates predicting housing prices using the California Housing dataset. I use a mix of traditional regression models and a deep learning model for comparison.

## Dataset
- California Housing Dataset: Contains features like average income, house age, and more for California districts, with the target being the median house value.

## Models Used
- Linear Regression
- Random Forest Regressor
- Neural Network (Keras Sequential Model)

## Evaluation Metrics
- Mean Squared Error (MSE)
- R^2 Score

## Results
- Linear Regression: MSE = 0.556, R^2 = 0.576
- Random Forest: MSE = 0.255, R^2 = 0.805
- Neural Network: MSE = 0.344, MAE = 0.402

## Tools & Libraries
- scikit-learn: Data preprocessing, baseline models
- Keras: Neural network model
- Matplotlib/Seaborn: Data visualization

## Future Improvements
- Hyperparameter Tuning: Adjust model parameters to improve accuracy.
- Feature Engineering: Create more informative features to enhance model performance.

