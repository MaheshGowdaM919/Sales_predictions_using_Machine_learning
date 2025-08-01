# Sales_predictions_using_Machine_learning
The main goal is to build, evaluate, and interpret linear regression models to predict future sales based on advertising budgets.

This repository contains a Jupyter Notebook that explores the fundamentals of linear regression for sales prediction. The project uses a sample advertising dataset to demonstrate how different advertising channels (TV, Radio, Newspaper) affect sales.

## Table of Contents

- [Project Overview](#project-overview)
- [Key Concepts Covered](#key-concepts-covered)
- [Dataset](#dataset)
- [Model Interpretation](#model-interpretation)
- [Feature Engineering](#feature-engineering)
- [Assumptions of Linear Regression](#assumptions-of-linear-regression)
- [Dependencies](#dependencies)

## Project Overview

This notebook serves as a practical introduction to regression analysis, a powerful predictive modeling technique. It walks through the process of building, evaluating, and interpreting linear regression models.

The primary goal is to answer questions like:
- Is there a relationship between advertising spend and sales?
- How strong is this relationship?
- Which advertising channels have the most significant impact on sales?
- Can we predict future sales based on a given advertising budget?

## Dataset

The project uses a simple `advertising.csv` dataset, which contains:
- **Features**: `TV`, `Radio`, and `Newspaper` advertising spend (in thousands of dollars).
- **Response**: `Sales` (in thousands of widgets).


## Model Interpretation

The notebook demonstrates how to interpret the model's output, including the meaning of:
- **Coefficients**: The change in sales for a one-unit change in an advertising channel's spending.
- **P-values**: The probability that a feature has no relationship with sales. A low p-value suggests the relationship is statistically significant.
- **R-squared**: The proportion of the variance in sales that is predictable from the advertising variables.

## Feature Engineering

The notebook also shows how to handle more complex data, such as:
- **Binary Categorical Features**: Creating dummy variables to represent categories like `large` or `small` markets.
- **Multi-Category Features**: Using multiple dummy variables to represent categories like `rural`, `suburban`, or `urban` areas.

## Assumptions of Linear Regression

A dedicated section of the notebook is included to review the critical assumptions of linear regression:
- **Linearity**
- **Multivariate Normality**
- **No Multicollinearity**
- **No Autocorrelation**
- **Homoscedasticity**

This section is essential for understanding the limitations and proper application of the linear regression model.

## Dependencies

- `pandas`
- `matplotlib`
- `scikit-learn`
- `statsmodels`
- `numpy`

