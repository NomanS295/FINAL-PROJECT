=======
# FINAL-PROJECT 

## Overview

### Breast Cancer

Breast cancer is the second most common type of cancer in Canadian women, behind only skin cancer. While it can be found in men, it is a much rarer occurrence.  It is estimated that approximately 27,000 Canadian women will be diagnosed this year with breast cancer. 1 in 8 women are expected to develop breast cancer within their lifetime and 1 in 33 will die from it.

### Purpose

The purpose of our analysis is to study malignant(cancerous) and benign(non-cancerous) tumors. Using the information gathered paired with machine learning, we hope to predict weather a tumor is more likely to be malignant based on it's characteristics.

## Data Cleaning and Analysis
For data cleaning an analysis, Pandas will be used in tools such as the Jupyter Notebook development environment in order to process and clean the data. The Kaggle NBA data as well as data extracted from basketball-reference.com are both in csv formats, which pandas offers easy ways to import and process the data with dataframes, doing things like easily checking for duplicates and missing data.

 

## Machine Learning
SciKitLearn will be used as the Machine Learning library to process our basketball data. With the kaggle data spanning many years and the individual player data, there should be a significant amount of data points in order to train the machine learning model for the players and test on data on other years. The target for our prediction will be predicting player's performance in the next year. To create one target data point for our model to predict, we will use "game score" which is a statistic used to try to encapsulate multiple aspects of a player's performance and incorporates multiple statistics in it's calculation. As we experiment with the datasets, the machine learning models employed and the process may change. 


## Databases
For now, we are considering the use of MongoDB as a flexible NoSQL database which can be managed with tools like Compass as a GUI for the data, as well as potential integration into tools like Flask if we consider it for future parts of the project.


## Dashboard
The current plan for creating a Dashboard will be taking the data we produce and using it in Tableau to display and share the data, as a flexible tool we can use with the data we have. We will be rexamining our needs and other possible ways to create a dashboard as we progress with the project.
