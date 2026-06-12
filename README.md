Overview

This project analyzes medical insurance cost data and develops a predictive model to estimate insurance charges using demographic and behavioral characteristics.

The objective was to identify the primary drivers of insurance costs and evaluate how accurately a linear regression model could predict individual medical expenses.

Dataset

The dataset contains information on 1,338 insured individuals, including:

Age
Sex
BMI
Number of Children
Smoking Status
Region
Annual Medical Charges

Tools Used:
Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Jupyter Notebook

Results:

Model Performance:

R²: .7836
MAE: $4181
RMSE: $5796

Key Findings:

Smoking has the strongest impact on predicted insurance charges.
Age and BMI are positively linked to higher charges.
Geographic location does not have a significant impact on charges.
This model explains approximately 78% of variation in the charges.
