## Overview
This repository contains the analysis of a bank marketing dataset using a logistic regression model to predict whether a client will subscribe to a term deposit. The logistic regression approach is explored in detail to provide insights into its performance and predictive power using various metrics and data visualizations.

## Dataset Description
The dataset is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).
Attributes:

- age: Age of the client (numeric)
- job: Type of job (categorical)
- marital: Marital status (categorical)
- education: Education level (categorical)
- default: Has credit in default? (binary)
- balance: Average yearly balance, in euros (numeric)
- housing: Has housing loan? (binary)
- loan: Has personal loan? (binary)
- contact: Contact communication type (categorical)
- day: Last contact day of the month (numeric)
- month: Last contact month of year (categorical)
- duration: Last contact duration, in seconds (numeric)
- campaign: Number of contacts performed during this campaign and for this client (numeric)
- pdays: Number of days that passed by after the client was last contacted from a previous campaign (numeric)
- previous: Number of contacts performed before this campaign and for this client (numeric)
- poutcome: Outcome of the previous marketing campaign (categorical)
- y: Has the client subscribed to a term deposit? (binary, target variable)
  
## Files
Logistic_Regression_Bank_Marketing.ipynb: Jupyter notebook with the logistic regression analysis.

## Requirements
To run the notebook, you need Python installed along with the following libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
