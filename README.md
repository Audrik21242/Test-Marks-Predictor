in this project, we build a model that predict the marks of the students based on various features
The model will be built using numpy and pandas for preprocessing, seaborn for visualization and sklearn for model selection building
IN this project we have selected to divide our dataset into training and testing data.
Additionally, on plotting the relationships among the features, we obseerved that features math, reading and writing scores were dependent on each other whereas they were not really affected by other features
Therefore, hese three features were extracted and the model was trained on them.
The preprocessing involved the above mentioned steps to find relationships among the features as well as label encoding and scaling the columns
In our project we make the prediction on the reading, writing and math scores and for that, we use a variety of models. These are Linear regression, SVR, decision tree regressor and random forest regressor
For evaluation we check the r2 score as well as calculate the model score
The best result for math marks prediction was with linear regression with an r2 score of 0.554 and a model score of 0.706 followed by RFR with 0.506 r2 and 0.60 model score
for reading marks the best was with linear regression with r2 score being 0.917 and moedl score being 0.90 followed by rfr with r2 0.859 and model score being .899
for writing the best was with linear r2 score :  0.9023478894078029 and model score :  0.9141278133486234 followed by rfr r2 score :  0.8819148296910767 model score :  0.8943864854094494

The worst performing model for each prediction was SVR
