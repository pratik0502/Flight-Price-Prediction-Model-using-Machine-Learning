# Flight-Price-Prediction-Model-using-Machine-Learning

## Aim: 
Develop a machine learning model to predict flight prices based on various factors.

## Target: 
Create a model with high accuracy that can predict flight prices accurately.

## Description:
In this project, we have collected a dataset containing information about flights, including airlines, departure time, arrival time, source city, destination city, duration, stops, class, and price. We aim to build a regression model that can predict the flight prices accurately based on these features.

We start by importing the necessary libraries and loading the dataset into two separate dataframes. Then, we concatenate the dataframes to create a single dataframe for analysis. We perform data exploration and preprocessing steps such as handling missing values, encoding categorical variables, scaling numerical features, and dropping unnecessary columns.

Next, we split the dataset into training and testing sets and apply the necessary transformations using one-hot encoding and ordinal encoding for categorical variables. We also scale the duration feature using standardization. We train a linear regression model on the transformed training data and evaluate its performance on the testing data using the R-squared metric.

Additionally, we perform cross-validation to validate the model's performance and assess its generalization capabilities. Finally, we analyze the results, draw conclusions, and discuss the accuracy achieved by the model in predicting flight prices.

## Conclusion: 
The developed machine learning model based on linear regression achieved an accuracy of 92% on the testing data. Cross-validation results showed an average accuracy of 91% on the training data, indicating good generalization capabilities. The model can be utilized to predict flight prices based on various factors and can be valuable for both airlines and customers in making informed decisions regarding flight bookings.
