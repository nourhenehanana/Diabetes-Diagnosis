# Diabetes-Diagnosis
the objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the datsaset.
All patients are females of at least 21 years of age of Pima Indian heritage. 
The dataset consist of several medical predictor variables and one target variable, outcome. 
Predictor variables include the number of pregnancies the patients have had, their BMI, insulin level, age , and so on. 

We perform ensemble learning by boosting techniques used on decision trees: 

Perform XGboost on data by splitting the trainset on 10 consuctive folds and perfrom the cross validation score where accuracy = 0.7499

Perform AdaBoost on data and accuracy achieved = 0.7552
