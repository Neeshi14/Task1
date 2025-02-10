# Task1
perform EDA on dataset
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

# Data Preprocessing & Cleaning

Some columns (Glucose, Blood Pressure, Skin Thickness, Insulin, BMI) contain zero values, which are likely missing data.

We replaced zeros with NaN and then filled missing values using the median to maintain data integrity.

Checked for outliers using boxplots to ensure data consistency.


# Exploratory Data Analysis (EDA)

Descriptive Statistics: Summary of each column (mean, median, etc.).

Visualizations:

Histogram & Boxplots: Understand the data distribution.

Correlation Heatmap: Identify relationships between variables.

Pie Chart: Distribution of diabetic vs. non-diabetic individuals.


# Goal of the Dataset

This dataset is primarily used for training Machine Learning models to predict whether an individual has diabetes based on input features.



# Next Steps

Feature engineering & scaling for better model performance.

Training models like Logistic Regression, Decision Trees, Random Forest, Linear Regression , support Vector machine and KNN .

And then calculate the Accuarcy , MSE and RMSE.


#  Formulas for Accuracy, MSE, RMSE, and Confusion Matrix


1️⃣ Accuracy (for Classification)
Accuracy measures the percentage of correctly classified instances out of the total instances.

$$ Accuracy = \frac{TP + TN}{TP + TN + FP + FN} $$
The formula for accuracy is $ Accuracy = \frac{TP + TN}{TP + TN + FP + FN} $.

 
Where:

TP (True Positives) → Correctly predicted positives
TN (True Negatives) → Correctly predicted negatives
FP (False Positives) → Incorrectly predicted as positive
FN (False Negatives) → Incorrectly predicted as negative
✅ Higher accuracy means a better model, but it may not be reliable for imbalanced datasets.
