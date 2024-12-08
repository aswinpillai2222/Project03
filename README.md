# Project03 - Health Insurance Charge Prediction using Machine Learning
This work demonstrates the potential of machine learning in personalized insurance pricing. Insurance companies can leverage such models to calculate fair premiums and identify high-risk individuals, while public health officials can use the findings to promote healthier lifestyles and lower healthcare costs.

Overview
This project predicts health insurance charges based on factors such as age, sex, BMI, children, smoker status, and region. By using machine learning techniques, the project demonstrates the practical application of data analysis and regression models in the insurance industry.

Features
Data preprocessing: Handling missing values, outlier removal, and feature scaling.
Categorical variable encoding for sex, smoker status, and region.
Regression model implementation and evaluation.
Visualizations to interpret results and highlight key factors affecting charges.
Dataset
The dataset includes the following columns:

age: Age of the individual.
sex: Gender (male or female).
bmi: Body Mass Index, a measure of body fat.
children: Number of dependents.
smoker: Smoking status (yes or no).
region: Residential region (northeast, southeast, etc.).
charges: Medical insurance cost in dollars.
Methodology
Data Preprocessing:

Imputation of missing values with column means.
Removal of outliers using the IQR method.
Encoding categorical variables and scaling numerical features.
Model Training:

Built a Linear Regression model to predict charges.
Evaluated using metrics like MAE, MSE, RMSE, and R².
Results:

MAE: 0.37
MSE: 0.37
RMSE: 0.60
R²: 0.60
Visualizations
Scatter plots to show relationships between features and charges.
Bar graphs highlighting the influence of smoking and BMI on charges.
Conclusion
The project provides insights into how lifestyle factors like smoking and BMI significantly impact insurance costs. It demonstrates how machine learning can be used to assist insurers in pricing strategies and promoting healthier behaviors among policyholders.
