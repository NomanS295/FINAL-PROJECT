=======
# FINAL-PROJECT 

## Overview

### Breast Cancer

Breast cancer is the second most common type of cancer in Canadian women, behind only skin cancer. While it can be found in men, it is a much rarer occurrence.  It is estimated that approximately 27,000 Canadian women will be diagnosed this year with breast cancer. 1 in 8 women are expected to develop breast cancer within their lifetime and 1 in 33 will die from it.

### Purpose

The purpose of our analysis is to study malignant(cancerous) and benign(non-cancerous) tumors. Using the information gathered paired with machine learning, we hope to predict weather a tumor is more likely to be malignant based on it's characteristics.

## Data Cleaning and Analysis
For data cleaning and analysis, Pandas will be used in tools such as the Jupyter Notebook development environment in order to process and clean the data. The reference CSV pulled from the Kaggle database was largely complete for analysis, but Jpyter Notebook and Database software was used to confirm whether data was missing or needed further cleaning or adjustment.

 

## Machine Learning
SciKitLearn will be used as the Machine Learning library to process our cancer data. Logistic regression is the main classification tool we use for the analysis of all the data going into the supervised ML model. Logistic Regression was the method used to analyze the data, further boosted and compared to other methods including Adaptive Boosting and Random Forest methods, although the boosting methods only showed minor improvements to the results of the initial linear regression.


## Databases
For now, we are considering the use of MongoDB as a flexible NoSQL database which can be managed with tools like Compass as a GUI for the data, as well as potential integration into tools like Flask if we consider it for future parts of the project.


## Dashboard
The current plan for creating a Dashboard will be taking the data we produce and using it in Tableau to display and share the data, as a flexible tool we can use with the data we have. We will be rexamining our needs and other possible ways to create a dashboard as we progress with the project.
