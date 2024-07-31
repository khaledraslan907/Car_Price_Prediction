# Car_Price_Prediction
A linear and Lasso Regression Model for Car_Price_Prediction
# Project Overview:
# 1- Loading the Dataset:
The dataset is loaded using the pandas library. This step involves reading the dataset file into a DataFrame for easy manipulation and analysis.
# 2- Exploring and Describing the Data:
Several methods are employed to understand the dataset better as head, shape, describe and info.
# 3- Encoding the Data:
Categorical features in the dataset are encoded using the Label Encoder method. This converts categorical variables into a numerical format, which is required for the regression models.
# 4- Splitting the Data:
The dataset is divided into training and testing sets using the train_test_split function. This step is crucial for evaluating the performance of the models on unseen data.
# 5- Building and Training the Models:
Two types of regression models are built:
# Linear Regression: 
A simple regression model that assumes a linear relationship between the features and the target variable (car price).
# Lasso Regression: 
A regularized version of linear regression that includes an L1 penalty to encourage sparsity in the model coefficients, potentially improving model performance by eliminating less important features.
# 6- Model Evaluation:
The performance of both models is evaluated using metric of R-squared (R²). This metrics helps in understanding how well the models are performing in predicting car prices.
