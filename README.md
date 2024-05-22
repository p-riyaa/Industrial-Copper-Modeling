# Industrial-Copper-Modeling

## Introduction
The goal of this project is to develop a machine learning solution that predicts the selling price of copper based on historical transaction data and classifies the status of each transaction.Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the selling price and leads accurately.

## Regression model details
The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, outlier detection and handling, handling data in wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm.

## Classification model details
Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. You can use the STATUS variable with WON being considered as Success and LOST being considered as Failure and remove data points other than WON, LOST STATUS values.

# Tools Installed  
PyCharm Community Edition 2023.3.3 , Jupyter/Google Colab
# Required Libraries 
Streamlit, numpy, pandas, scikit-learn, Image, re

# User Guide 

**Step 1** - Home Tab provides a brief overview of the project. 
**Step 2** - Predict selling price Tab allows predict selling price based on the given input values.
**Step 3** - Predict status Tab allows to predict status(WON/LOST) based on the given input values.
