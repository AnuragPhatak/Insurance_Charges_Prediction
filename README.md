# Project Overview

This repository contains a regression model built to predict insurance charges based on patient demographic and health information. The model has been trained and evaluated using a variety of techniques to achieve an R-squared score of 87% on the test data.

## Primary Goal
The primary goal of this project is to predict medical charges for individuals based on features such as:
- Age group
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region of residence

## Key Features of the Project:

### Data Preprocessing:
- **Encoding categorical variables** using One-Hot Encoding and Ordinal Encoding.
- **Capping outliers** using the Winsorization technique to handle extreme values in features like BMI and charges.

### Feature Engineering:
- Identified and removed **influential points** using Cook’s Distance to improve model performance.
- Applied **scaling** to continuous variables (e.g., BMI) for better model convergence.

### Modeling:
- Used **Ordinary Least Squares (OLS)** regression for model building.
- Achieved **87% R-squared** score after model tuning and evaluation.

### Residual Analysis:
- Performed **residual analysis** to identify and address non-linear relationships and patt
