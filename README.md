=======
# FINAL-PROJECT 

## Overview

## Data Cleaning and Analysis
For data cleaning an analysis, Pandas will be used in tools such as the Jupyter Notebook development environment in order to process and clean the data. The Kaggle NBA data as well as data extracted from basketball-reference.com are both in csv formats, which pandas offers easy ways to import and process the data with dataframes, doing things like easily checking for duplicates and missing data.

 

## Machine Learning
SciKitLearn will be used as the Machine Learning library to process our basketball data. With the kaggle data spanning many years and the individual player data, there should be a significant amount of data points in order to train the machine learning model for the players and test on data on other years. The target for our prediction will be predicting player's performance in the next year. To create one target data point for our model to predict, we will use game score which is a statistic used to try to encapsulate multiple aspects of a player's performance and encorporates multiple statistics in it's calculation. As we experiment with the datasets, the machine learning models employed and the process may change. 

## Purpose
  The main reason that we have created this model is for NBA team owners and scouters to take a look at player statistics and based off of that they can decide how much they think each player should get paid based off the model. There are many teams in the NBA that have players that are over or underpaid and the model that we have created can help understand player performances based off of age and seasons. 

Basketball is a sport where players usually tend to decline as they grow older but there are many players that still have good performances regardless of their age. Our machine learning model will take a look at multiple players performances as an example and demonstrate to team owners how the model can be useful and help them save money and know what players to trade or keep in the roster.

## Databases
For now, we are considering the use of MongoDB as a flexible NoSQL database which can be managed with tools like Compass as a GUI for the data, as well as potential integration into tools like Flask if we consider it for future parts of the project. 

## Dashboard
The current plan for creating a Dashboard will be taking the data we produce and using it in Tableau to display and share the data, as a flexible tool we can use with the data we have. We will be rexamining our needs and other possible ways to create a dashboard as we progress with the project.
