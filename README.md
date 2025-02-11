# Task1
perform EDA on dataset
# Exploratory Data Analysis (EDA)

Descriptive Statistics: Summary of each column (mean, median, etc.).

Visualizations:

Histogram & Boxplots: Understand the data distribution.

Correlation Heatmap: Identify relationships between variables.

Pie Chart: Distribution of diabetic vs. non-diabetic individuals.
# Data Preprocessing & Cleaning

Some columns (Glucose, Blood Pressure, Skin Thickness, Insulin, BMI) contain zero values, which are likely missing data.

We replaced zeros with NaN and then filled missing values using the median to maintain data integrity.

Checked for outliers using boxplots to ensure data consistency.
# Task2 
understand the basic information about the dataset


Here we are using the diabetes dataset.

| Column Name                 | Description                                              |
|-----------------------------|----------------------------------------------------------|
| **Pregnancies**             | Number of times a woman has been pregnant               |
| **Glucose**                 | Blood glucose concentration (mg/dL)                     |
| **BloodPressure**           | Diastolic blood pressure (mm Hg)                        |
| **SkinThickness**           | Thickness of skin fold (mm)                             |
| **Insulin**                 | Insulin level in blood (mu U/ml)                        |
| **BMI**                     | Body Mass Index (weight/height²)                        |
| **DiabetesPedigreeFunction**| Genetic risk factor (higher value = higher risk)       |
| **Age**                     | Age of the individual                                  |
| **Outcome**                 | Diabetes status (0 = No, 1 = Yes)                      |





# Goal of the Dataset

This dataset is primarily used for training Machine Learning models to predict whether an individual has diabetes based on input features.



# Next Steps

Feature engineering & scaling for better model performance.

Training models like Logistic Regression, Decision Trees, Random Forest, Linear Regression , support Vector machine and KNN .

And then calculate the Accuarcy , MSE and RMSE.



# 1)  Linear Regression :
   Linear Regression is a supervised learning algorithm used for predicting a continuous numerical value based on given input features. It assumes a linear relationship 
   between the dependent (target) variable and one or more independent (predictor) variables.

# 2)  Logistic Regression :
   Logistic Regression is a supervised machine learning algorithm used for classification problems. It predicts the probability 
   that a given input belongs to a particular class, typically in binary classification (e.g., Yes/No, 0/1, True/False).

# 3)  Support vector Machince :
   Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression tasks. It is 
   widely used for binary classification, but it can also handle multi-class problems.

# 4)  KNN(k-Nearest Neighbor) :
   K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for classification and regression tasks. It is based on the idea that data points with similar 
   features tend to be near each other.

 # 5) Decision Tree :
   A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It works like a flowchart, where each internal node represents a 
   decision based on a feature, branches represent outcomes, and leaf nodes represent final predictions.

# 6) Random Forest Tree:
   Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their outputs to improve accuracy and reduce overfitting. It is commonly 
   used for classification and regression tasks.






