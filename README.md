# Student Marks Prediction
This project builds a model to predict students' marks based on various features, using machine learning techniques to analyze relationships and dependencies among scores.

# Table of Contents
1. Project Overview
2. Libraries and Dependencies
3. Data Preprocessing
4. Model Selection and Training
5. Evaluation Metrics
6. Results
7. Conclusion


# Project Overview
The aim of this project is to predict student marks based on specific features. Through data exploration, we observed that the features for math, reading, and writing scores have significant dependencies on each other but minimal correlation with other features. Consequently, we focused on these three features for training our model.

# Libraries and Dependencies
The project uses the following libraries:<b/>
<b/>
NumPy and Pandas: For data preprocessing and manipulation.<b/>
Seaborn: For visualizing feature relationships.<b/>
Scikit-Learn (sklearn): For model selection, building, and evaluation.<b/>


# Data Preprocessing
Data Splitting: The dataset is divided into training and testing sets.<b/>
Feature Selection: After analyzing feature dependencies, the math, reading, and writing scores were selected as primary predictors due to their interdependence.<b/>
* Preprocessing Techniques:
  - Label Encoding: Applied to categorical variables.
  - Feature Scaling: Used to standardize the dataset for consistent model performance.


# Model Selection and Training
A variety of regression models were tested to predict math, reading, and writing scores:
<b/>
* Linear Regression
* Support Vector Regressor (SVR)
* Decision Tree Regressor
* Random Forest Regressor


# Evaluation Metrics
The models were evaluated using:
R² Score: Measures the proportion of variance explained by the model.<b/>
Model Score: An additional metric to assess the accuracy of predictions.<b/>
<b/>

# Results
The best and worst-performing models for each score prediction are as follows:

1. Math Marks Prediction
 - Best Model: Linear Regression
   - R² Score: 0.554
   - Model Score: 0.706
 - Second Best: Random Forest Regressor (RFR)
   - R² Score: 0.50
   - Model Score: 0.60

2. Reading Marks Prediction
- Best Model: Linear Regression
  - R² Score: 0.917
  - Model Score: 0.90
- Second Best: Random Forest Regressor (RFR)
  - R² Score: 0.859
  - Model Score: 0.899

3. Writing Marks Prediction
- Best Model: Linear Regression
  - R² Score: 0.902
  - Model Score: 0.914
- Second Best: Random Forest Regressor (RFR)
  - R² Score: 0.882
  - Model Score: 0.894

* Worst Performing Model (Across All Scores): Support Vector Regressor (SVR)

# Conclusion
Linear Regression emerged as the most effective model for predicting student marks in math, reading, and writing. The Random Forest Regressor provided competitive performance, but SVR was consistently the least effective across all predictions.
