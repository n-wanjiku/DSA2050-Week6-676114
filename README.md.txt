# DSA2050 Week 6: Guided Regression Lab

## Student Information
* **Name:** [Your Name]
* **Student ID:** [Your Student ID]

## Lab Objective
Predict sales revenue (`Sales_KES`) using supervised regression techniques, evaluate predictive performance, and conduct error and sensitivity analyses.

## Models Compared
* Mean Baseline
* Median Baseline
* Linear Regression
* Ridge Regression
* Decision Tree Regressor

## Best Model
* Ridge Regression / Linear Regression

## Selected Model MAE
* KES 13,736.32

## Key Findings
1. Linear models significantly outperform baselines and tree-based models, reducing average prediction errors by over 60% and achieving an $R^2$ of ~0.87.
2. Removing `AdvertisingSpend_KES` causes a severe drop in performance ($R^2$ falling to ~0.69), confirming advertising spend as a primary driver of sales revenue.

## Limitations
1. **Small Dataset:** The dataset contains only 320 rows, limiting generalization and increasing sensitivity to outliers.
2. **Missing External Factors:** Lacks crucial external features such as competitor pricing, regional macroeconomic indicators, and promotional timing.
3. **Correlation vs. Causation:** Coefficients reflect historical associations rather than direct causal levers.