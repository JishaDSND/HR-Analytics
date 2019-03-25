# Human Resource Analytics


Why are our best and most experienced employees leaving prematurely?

Human Resource Analytics

(Blog Writeup for Udacity DSND)

Table of Contents:

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
Other models from sklearn