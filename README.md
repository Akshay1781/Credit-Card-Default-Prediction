# Credit-Card-Default-Prediction

![image](https://user-images.githubusercontent.com/101791277/187669173-3e2d9a85-94a1-4074-9df8-593557e00d19.png)

## 1. Business Problem

The objective of this project is to predict which customer might default in coming months. The research aims at developing a mechanism to predict the credit card default beforehand and to identify the potential customer base that can be offered various credit instruments so as to invite minimum default.

## 2. Solution Strategy

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

## 3. Top 3 Data insights

No. of defaulters have a higher proportion of educated people (graduate school and university)

Customers with high credit limits tend to pay the pay on time and hence are not defaulters.

Imbalance in the target class which is balanced using SMOTE

## 4. Machine learning models implemented

Logistic Regression, Decision Tree, KNN Classifier, XGBoost Classifier, Naive Bayes, SVM.

## 5. Conclusion

XGBoost Classifier, Logistic Regression classifier and SVM Classifier give highest accuracy score of a customer is likely to default next month.

Using K-Nearest Neighbour classifier we predict 78% accuracy and Decision Tree Classifier give 73% accuracy a customer is likely to default next month.

Naive bayes classifier gives the lowest accuracy of 58%.
