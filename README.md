# Crop Production Prediction using Machine Learning

![image](https://github.com/Simrank10/Crop-Production-Prediction/assets/105905798/1c86ceff-6a58-4864-933e-9b656306647d)


## Overview

This project aims to predict crop production using machine learning techniques. The goal is to provide accurate predictions of crop yields based on the season it is grown, area used for cultivation and the State, district the crop is grown. By leveraging historical data and advanced predictive models, farmers can make informed decisions to optimize crop production and maximize yields based on the season and area.

## Dataset

The dataset used for this project contains historical information about crop yields, focusing on crops such as rice and wheat, along with data on the year, season, area, and production. The dataset was sourced from [This link](https://www.aps.dac.gov.in/APY/Index.htm) . Initially, the dataset was in an unstructured format, which was then transformed into an Excel file and preprocessed to remove missing values, normalize features, and prepare it for training machine learning models using Python.

## Preprocessing
Before training machine learning models, the dataset underwent preprocessing steps to ensure its suitability for model training. This included handling missing values, normalizing features, and encoding categorical variables. Python libraries such as pandas and scikit-learn were utilized for these preprocessing tasks.

## Data Visualisation
Exploratory data analysis was conducted to gain insights into the dataset and understand the relationships between different variables. Visualizations such as histograms, scatter plots, and correlation matrices were used to analyze the distribution of data and identify patterns. Also, an interactive dashboard was created using PowerBI.

## Model Selection and Training
Several machine learning algorithms were explored for predicting crop production, including linear regression, decision trees, random forests, and gradient boosting. These models were trained on the preprocessed dataset using a LazyRegressor library to check for the best fit model rather then fitting individually each model over the data. This allowed for comparison between different models and identification of the most accurate predictive model of crop production.

## Model Evaluation
The performance of the trained model was evaluated using metrics such as mean squared error, mean absolute error, and R-squared score.

## Deployment
Once a suitable model was identified, it was deployed for practical use. This involved integrating the model into a user-friendly interface or application where farmers could input relevant data and receive predictions for crop production based on their specific conditions.

## Conclusion
In conclusion, this project demonstrated the potential of machine learning techniques in predicting crop production and helping farmers make informed decisions to optimize their yields. By leveraging historical data and advanced predictive models, farmers can improve their agricultural practices and contribute to food security and sustainability.
