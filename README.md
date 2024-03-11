## Overview of the Analysis

* The purpose of this was to train and understand machine learning models. We wanted to use machine learning for loan risks. The goal was to build a model that can help someone identify creditworthyness of borrowers.

* The financial information that we had were looking at was loan status. Loan_size, interest_rate, borrower_income, debt_to_income,num_of_accounts, derogatory_marks, total_debt, and loan_status were used for example.

* I added a value counts to understand the loan status. The value set of 0 was 75036 for healthy, and the vlaue set of 1 had 2500 for high risk.

* The stages of the mahcine learning process were to create a datafram from the data I had, and then split the data intot two groups, training and testing. Make a logistic regression model and then make predictions based on the logistic regression model. The last stage is to evaluate my results. In this case I was looking at precision and accuracy scores.

* I used logistic regression to help calculate the probability of loan risk and to help indentify creditworthiness of borrowers.

## Results

![logreg](https://github.com/campbellthomas1/credit-risk-classification/assets/145702710/0de7adc6-2b67-4a82-b689-81a1ff7cecac)

* Machine Learning Model 1: Logistic Regression
    * For the models accuracy, in my opinion it does a good job at giving us information about the healthy and high risk loans and if they are predicted correctly. There is much more data for healthy loans though so...
    * The precision for this model is 100% for healthy loans and 87% for high risk loans. This makes sense but could also be looked into further being that the precision could vary based on the data given and the machine learning outcome.
    * The recall of the model was 100% for the healthy loans and 95% for the high risk loans. This means that 100% of healthy loans were calssified as correct and the high risk loans means that 95 were.

## Summary

* I would recommend this for company use being that it correctly predicted the healthy loans for precision and recall, with a high accuracy score as well. The only worry is the precision of the high risk loans being 87% and the recall being 95%. When dealing with high risk loans 15% precision and 5% recall may be a red flag? They would want those values as close to 99%-100%.
* It is also more important to be able to predict the high risk loans. With the data set being skewed with much more healthy loans the machine may not have had enough data to look at for the high risk loans? When you are looking at the creditworthiness of borrowers I think it is important to have a model that accurately predicts high risk loans, especially if a company wants to use the model to help them.
