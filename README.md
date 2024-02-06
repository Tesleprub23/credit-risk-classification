Module 20 Credit-Risk-Classification

Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. 
You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Instructions
The instructions for this Challenge are divided into the following subsections:
Split the Data into Training and Testing Sets
Create a Logistic Regression Model with the Original Data
Write a Credit Risk Analysis Report
Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  NOTE
  A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.
Split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
Generate a confusion matrix.
Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Analysis

  The purpose of this analysis is to create and evaluate the accuracy of the data model that predicts credit worthiness of potential borrowers. 
   A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
