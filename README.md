# House-Price-Prediction
# Installation
To run this project, you'll need to install the following libraries:

     pip install scikit-learn numpy
     
# What i built ?
- Implemented a basic simple linear regression.
- Evaluated model with RMSE and R².
- Visualized data fit and prediction accuracy.
# Why i built it ?
- Purpose: I've built a simple linear regression model to predict housing Price based on Area.
- Demonstration: It shows how linear regression can model the relationship between a predictor (Area) and a target (Price) for housing data.
- Evaluation: It's helps to understand model performance via metrics like RMSE and R².
# How i built it ?
- Dataset Used: A small sample dataset with Area and Price of houses.
- Modeling Steps:
     - Selected Area as the predictor (X) and Price as the target (y).
     - Split data into training and testing sets (train_test_split).
     - Fit a LinearRegression model from sklearn.
     - Made predictions on test data.
- Evaluation Metrics:
     - RMSE: Indicates prediction error magnitude.
     - R² Score: Shows how well Area explains Price variance.
- Visualizations:
Price vs Area: Scatter plot with regression line shows relationship.
Actual vs Predicted: Compares predictions to actual prices.
