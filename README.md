Background

Each row in the dataset provide details (Geography, Gender, Age, Tenure, have credit cards,No. of products subscribed, salary) of customers of a bank.

Business objective: To predict the likelihood and factors leading to customers churning from the bank.

Dataset contains 14 variables.

Dataset link: https://www.kaggle.com/datasets/shubh0799/churn-modelling/data

Target variable: 'Exited' (1,0)

The Artificial Neural Network classifier is used for predictive modelling.

Accuracy rate of ANN classifer = 86%

'Exited', target variable is imbalanced, therefore ROC_AUC score is used as the evaluation metric to evaluate the accuracy of all prediction models.
(Receiver Operating Characteristics - Area Under Curve) metric tells how much the prediction model is capable of distinguishing between both classes, in this case: Churn or No churn.

XGBoost Classifier has the highest AUC score = 0.737

Factors: Associated with bank customers' churn:

1) 44 to 56 years, 2) No. of bank products owned, 3) Is customer an Active member, 4) 57 to 69 years 5) Germany customers
