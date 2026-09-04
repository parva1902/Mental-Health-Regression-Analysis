# Mental-Health-Regression-Analysis
Data analysis and regression modeling project investigating factors influencing mental health score using python. 

Project Overview

This project involves analyzing the factors that determine mental health scores through statistical analysis and regression modeling, using Python.

There are a total of 20 variables in the dataset, which include 19 independent variables and 1 dependent variable, which is the mental health score.

The key aim of the project is to determine the most important variables that influence mental health and build a model that predicts mental health scores.


#Objectives
Study the factors related to mental health scores
Clean the data and do exploratory data analysis
Use statistical methods for regression analysis
Identify significant predictors in the final model
Compare the various regression models
Validate the assumptions of the regression model
Interpret the findings and factors affecting mental health


# Regression Models Applied
The project considered different regression models:

1. Simple Linear Regression
2. Multiple Linear Regression
3. Interaction Model
4. First Order Model
5. Second Order Model
6. Logarithmic Transformation Model


# Data Preparation & Analysis
The analysis included:

1. Data cleaning
2. Summary statistics
3. Histograms
4. Box plots
5. Correlation analysis
6. Heatmaps
7. Feature selection
8. Conversion of qualitative variables
9. Forward selection
10. Backward elimination
11. Multicollinearity analysis using VIF
12. Residual analysis
13. Q-Q plot analysis


# Model Evaluation
The first order regression model was able to give an adjusted R-squared value of 0.926.

Interaction model incorporating anxiety and depression gave an R-squared value of 0.927.

Some of the second order and log transformation models were also considered. However, the log transformation model was rejected owing to its high Variance Inflation Factor (VIF), even though the R-squared value was high.


# Significant Variables
The final analysis identified eight significant variables:

1. Exercise Frequency
2. Social Support Level
3. Work Stress Level
4. Financial Stress
5. Social Media Usage
6. Anxiety Level
7. Depression Level
8. Work-Life Balance


# Final Model
The final regression model was:

Mental Health Score = 100.61
1.92 × Exercise Frequency
2.77 × Social Support Level
− 2.95 × Work Stress Level
− 1.91 × Financial Stress
− 0.86 × Social Media Usage
− 2.92 × Anxiety Level
− 3.94 × Depression Level
+ 3.53 × Work-Life Balance


# Key Findings
The results show that there is a positive correlation between exercise, social support, and work-life balance and mental health scores.

There is a negative correlation between high amounts of work-related stress, financial stress, anxiety, and depression with mental health scores.

The results have shown that through statistical analysis and regression models, important predictors of mental well-being can be found.


# Tools & Technologies
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Statsmodels
6. Matplotlib
7. Seaborn
8. Google Colab
9. Jupyter Notebook


# Project Structure
Mental-Health-Regression-Analysis/
│
├── README.md
│
├── src/
│   └── mental_health_analysis.py
│
├── report/
│   └── DSC423_Report.pdf
│
├── images/
│   ├── correlation_heatmap.png
│   ├── histograms.png
│   ├── boxplots.png
│   ├── residual_plot.png
│   └── qq_plot.png
│
└── requirements.txt


# Future Work
Future improvements could include using larger datasets and exploring advanced machine-learning techniques to further investigate factors associated with mental health.

# Author
# Parva Patel
