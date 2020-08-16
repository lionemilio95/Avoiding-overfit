# Avoiding-overfit
This is a Kaggle project that focusing on machine learning. There are only limited training data so it could easily cause overfit. 
Our goal is to avoid overfitting and increase the prediction accuracy.


We first tried seveal machine learning packages such as XGBoost, Random Forest, Support Vector Classification, Stochastic gradient descent, Linear Regression to make the predction of the test set. Although we carefully tune the parameters, none of them led to a satisfactory result. Therefore, we then tried a method called LB Probing which utilized the score and coefficients for each variables in the train set. After numerous trials, we finally get a decent Kaggle score for this problem. 
