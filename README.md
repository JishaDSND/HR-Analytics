# Human Resource Analytics
### The goal of HR analytics
Human resources analytics will aim to provide an organization with insights for efficiently managing employees to ensure business goals could be attained fast and efficiently. The challenge of human assets analytics would be to identify what information should be recorded and how to use the information to model and forecast capacities so that the organization gets the best return on investment (ROI) onto its human funding.

HR departments are creating more data than ever before, but at the same time, they frequently struggle to turn their information into valuable insights. This is where Machine Learning comes in. These decision-making models, when provided with the data and information, can deliver excellent error-free decisions, catch important trends in the data and provide actionable insights, which can be used to help propel the growth of the organization.

## Why are our best and most experienced employees leaving prematurely?
### In this analysis the business problem is 
    1. Why the best employees of this company are leaving pre-maturely.
    2. The company also wants us to predict which employees will be leaving next.
    3. What are the most significant factors affecting attrition?

Blog link : https://medium.com/@studyammu/why-employees-are-leaving-the-organization-7248b7c638e2

# Files in the repository
   1. HR_comma_sep.csv file from kaggle competition : Human Resource Analytics  
   2. HR_analytics_Report jupyter notebook
   3. Data_cleaning,data_visualization,statistical_modelling scripts for further use with detailed explanation.

## Table of Contents:

1. Data to insights

  1.1 Business Understanding
  
  1.2 Analytic Solution
  
  1.3 Feasability Study
  
  1.4 Analytical Base Table
  
2. Data Exploration

  2.1 Data Quality Report
  
  2.2 Data Cleaning
  
  2.3 Data Visualisation
  
    2.3.1 Conclusion
    
3. Statistical Modelling

  3.1 Modelling the satisfaction levels
  
  3.2 Modelling the Average monthly hours worked
  
  3.3 Modelling the Last evaluation scores
  
  3.4 Hypothesis Testing the correlations
  
  3.5 Conclusion
  
4. Machine Learning

  4.1 Parameter Fine Tuning
  
    4.1.1 KNeighborsClassifier
    
  4.2 Building the machine learning models
  
    4.2.1 Model Scores
    
    4.2.2 ROC Curve and AUC
    
    4.2.3 Scaling
    
    4.2.4 Feature Selection
    
  4.3 Observations
  
  4.4 Conclusion

# Imports:

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import numpy as np

import seaborn as sns

sklearn

##  Observation
####  From the visualizations carried out we have come to understand the following about the employees who left the firm:

  1. The employees who left the firm did indeed have a better performance than the employees who stayed with the firm.

  2. The employees who left the firm had lower satisfaction levels

  3. The employees who left the firm were made to work longer hours monthly.

  4. The management department stayed the longest number of years with the firm suggesting that the employees in the other departments could have had issues with the management.

  5. Employees who were given lesser projects were more likely to leave the firm.

  6. Employees having a mid level salary were more likely to leave the firm.

  7. Employees who worked really less number of hours or worked a high number of hours were more likely to leave the firm.

  8. Employee were more likely to leave the firm after working for 3 years.
 
 ## Conclusion

### After careful evaluation of the drawn observations, we can recommend the following to increase employee performance at an organization:

  1.Ensure a more improved rate of salary raises for the employees

  2. Create a more friendly, comfortable and inclusive office environment to have a better satisfaction level

  3. Reduce the number of project per employee to have the optimal workload and productivity

  3. Help upgrade the skill sets of the current employees, so as to make them suitable to take up more responsibilities and challenges, and in turn, prepare them for promotions
  
  
  
