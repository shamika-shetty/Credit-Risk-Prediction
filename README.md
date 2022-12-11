
# Credit Risk Prediction

The main objective of this project is to Minimization of risk and maximization of profit on behalf of the bank.To minimize loss from the bank’s perspective, the bank needs a decision rule regarding who to give approval of the loan and who not to. An applicant’s demographic and socio-economic profiles are considered by loan managers before a decision is taken regarding his/her loan application.

A predictive model developed on this data is expected to provide a bank manager guidance for making a decision whether to approve a loan to a prospective applicant based on his/her profiles.


## DataSet
The German Credit Data contains data on 20 variables and the classification whether an applicant is considered a Good or a Bad credit risk for 1000 loan applicants. 

Here is a link to the German Credit data - https://archive.ics.uci.edu/ml/datasets/South+German+Credit+%28UPDATE%29#

The dataset is in .asc file format, this is converted to .csv file(credit.csv)

## Approach

Different classification models like Logistic Regression, SVC,KNeighbors Classifier, Random Forest,Naive Bayes and XGBoost are built and out of this XGBoost gave highest accuracy and hyper parameter tuning also performed on this final model.

Deep neural network models are also crested by using tensorflow and keras.