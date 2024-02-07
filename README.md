Module 20 Credit-Risk-Classification

The purpose of this analysis is to create and evaluate the accuracy of the data model that predicts credit worthiness of potential borrowers. 
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Process
Create a Logistic Regression Model with the Original Data
Split the Data into Training and Testing Sets 
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. (10 points)
Split the data into training and testing datasets by using train_test_split. (15 points)
Create a Logistic Regression Model 
Fit a logistic regression model by using the training data (X_train and y_train). (10 points)
Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. (5 points)

Summary
•	The logistic regression model using the original data does a fabulous job of predicting the values for the 0 class (healthy loans) data. 
• The precision for the 1 class is 1.00 , meaning the model correctly made the positive prediction virtually every time. 
• The recall-the number of times the model correctly predicted a healthy transaction-was equally impressive for the 0 class at 0.99

The logistic regression model did not do quite as good a job predicting the values for the 1 class (high-risk loans). 
First, the precision rate, or the number of times the model correctly identified high-risk loans, was recorded at 0.85 or 85% . 
The recall-the number of times the model accurately predicted the high-risk loans versus the total number of high-risk loans-was 0.91
Overall though, the logistic regression model generated pretty impressive numbers for the model predictions.
