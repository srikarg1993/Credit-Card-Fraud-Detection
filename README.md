# Project Name - Credit Card Transaction Fraud Detection using Supervised Machine learning

## Repositiory File description
Project report - Contains the full description of the project
Project code - Python Jupyter notebook containing the full code with proper comments with instructions on how to run it in Google colab.
Data Quality report - Contains the data visualisations and initial analysis of data for fully understanding the given data.
Data Quality report code - Contains the code for the data quality report
Dataset - Card transactions data

## Dataset Description
Dataset Name: Card transactions data
Description: This dataset contains the information of the card transactions that have occurred in USA. It contains fields like Card number, merchant number, merchant description, and amount of the transaction. It also contains a fraud label field which tells whether the transaction is good or bad.
Time Period: 1 January 2006 – 31 December 2006
No. of Fields: 10
No. of Records: 96,753
Size of Dataset file: 7 MB

## Summary
Credit card fraud is a common type of identity theft which involves a fraudster stealing an individual's credit card or credit card information to make fraudulent purchases. Financial institutions must be able to accurately identify and stop fraudulent transactions in order to instill trust in their customer base and mitigate costs associated with these fraudulent transactions. Especially, the latest evolving fraud dynamics of counterfeit applications urge the banks to put a
premium on credit card fraud detection. On average, correctly identifying fraudulent transactions can save a bank around $2000 per fraudulent transaction therefore leading to large savings and increased customer satisfaction.

In this report, we have analyzed credit card transaction data filed by the US government to build several supervised models to successfully detect fraudulent transactions. The report covers our data preparation process and machine learning model tuning methods to allow insight for
stakeholders. Our main steps are as follows:

  - Data Preparation: Investigate data, analyze important field distributions, and fill in missing records.
  - Feature Engineering: Transform current data fields into new candidate variables that can improve model performance.
  - Feature Selection: Perform feature selection to find a subset of variables that are the strongest predictors of fraud.
  - Modeling: Train and test multiple ML models by using cross-validation and parameter tuning with GridSearchCV to identify the optimal model.
  - Analyzing Results: Determine ML model with best performance and make a recommendation for fraud detection threshold.

Our team built over 2,000 variables and narrowed it down to 20 strong indicator variables to feed into our models. We built out 5 different models, including a logistic regression, neural network, single decision tree, random forest, and boosted tree. Our analysis found the random forest model to have the best performance, with the ability to detect out of time (OOT) fraudulent transactions 59% of the time.

Given this information, we are confident in suggesting a fraud detection cut off rate of 5% which in this dataset would lead to savings of more than $1.56 million/year.


