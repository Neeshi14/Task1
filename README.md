#  Diabetes Prediction using Machine Learning

This project aims to predict whether an individual is diabetic based on health-related attributes using multiple machine learning algorithms. We use Exploratory Data Analysis (EDA), preprocessing, and various classification models to understand the dataset and improve prediction accuracy.

---

##  Task 1: Exploratory Data Analysis (EDA)

**Objective:** Analyze and understand the distribution, relationships, and quality of the data.

###  Descriptive Statistics
- Summary statistics (mean, median, std) for each feature.

###  Visualizations
- **Pie Chart**: Visualize the proportion of diabetic vs. non-diabetic individuals.
- **Box Plot**: visualize the numerical features
- **Histograms**: Examine the distribution and detect outliers.
---

##  Task 2: Data Preprocessing & Cleaning

Certain columns contain zero values that likely represent missing data:
- **Affected columns**: `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`

###  Cleaning Steps:
- Replaced zeroes with `NaN`.
- Filled missing values with the **median** to preserve data integrity.
- Checked for outliers using boxplots and handled accordingly.

---

##  Dataset Information

The dataset used is the **PIMA Indians Diabetes Dataset**.

| Column                     | Description                                                  |
|---------------------------|--------------------------------------------------------------|
| `Pregnancies`             | Number of times the individual has been pregnant             |
| `Glucose`                 | Blood glucose concentration                                  |
| `BloodPressure`           | Diastolic blood pressure (mm Hg)                             |
| `SkinThickness`           | Triceps skin fold thickness (mm)                             |
| `Insulin`                 | 2-hour serum insulin (mu U/ml)                               |
| `BMI`                     | Body Mass Index (weight in kg / (height in m)^2)             |
| `DiabetesPedigreeFunction`| A function that scores likelihood of diabetes based on family history |
| `Age`                     | Age in years                                                 |
| `Outcome`                 | Diabetes status (0 = Non-diabetic, 1 = Diabetic)             |

---

##  Next Steps

- Perform **feature engineering** and **scaling** for model performance.
- Train and evaluate various machine learning models:
  - Linear Regression
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest

- Evaluate model performance using:
  - **Accuracy**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**

---

##  Model Performance Comparison

| Model                  | Training Accuracy | Testing Accuracy | MSE       | RMSE     |
|------------------------|------------------|------------------|-----------|---------- |
| **Linear Regression**  | 76%              | 77%              | 0.1647    | 0.4058    |
| **Logistic Regression**| 76%              | 77%              | 0.2338    | 0.4835    | 
| **SVM**                | 77%              | 76%              | 0.2338    | 0.4835    |
| **KNN**                | 76%              | 67%              | 0.3246    | 0.5698    |
| **Decision Tree**      | 76%              | 69%              | 0.3051    | 0.5524    |
| **Random Forest**      | 76%              | 75%              | 0.2467    | 0.4967    |

---

##  Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

##  Conclusion

This project demonstrates how machine learning can be applied to predict diabetes using health-related parameters. Through EDA, preprocessing, and algorithm comparison, we gained valuable insights into the model performances and their limitations.



