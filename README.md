# Student-performance
Student stress and academic performance correlation analysis

## Overview

This project involves the analysis of student stress factors using data collected through a survey. The primary goal is to understand the relationship between various factors such as sleep quality, headaches, study load, extracurricular activities, and stress levels, and their impact on academic performance.



## Dataset

The dataset can be obtained from [here]('https://www.kaggle.com/datasets/samyakb/student-stress-factors/data']


## Data Preprocessing

Before conducting the analysis, several data processing steps were undertaken:

Checking for missing values (none found).
Identifying and handling duplicated rows (none present).
Exploring descriptive statistics to understand the distribution of numeric values.
Visualizing data through histograms to gain insights into the frequency distribution of responses.


## Correlation Analysis

A correlation matrix was computed to analyze the relationships between different factors. This step helped to identify potential connections and dependencies between variables.

## Regression Modeling

A linear regression model was implemented to predict academic performance based on selected features. The model coefficients and the coefficient of determination (R-squared) were examined. Additionally, an Ordinary Least Squares (OLS) regression model was applied to provide a more detailed statistical summary.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

## Future Work

Potential areas for future work include:

- Fine-tuning the model for better predictive performance.
- Exploring additional datasets to enhance the robustness of the analysis.
