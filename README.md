# Credit-Card-Fraud-Detection-Capstone-Project

## Problem Statement

In the banking industry, detecting credit card fraud using machine learning is not just a trend; it is a necessity for banks, as they need to put proactive monitoring and fraud prevention mechanisms in place. 

Machine learning helps these institutions reduce time-consuming manual reviews, costly chargebacks and fees, and denial of legitimate transactions.

## Objective:
Develop a machine learning model to detect fraudulent transactions using historical transactional data with a pool of merchants.

## Key Goals:

1) Analyze the business impact of fraudulent transactions.
2) Recommend cost-effective strategies to mitigate fraud risks.

## Project Pipeline
The project pipeline can be briefly summarised in the following steps:

 

Understanding Data: In this step, you need to load the data and understand the features present in it. This will help you choose the features that you need for your final model.

 

Exploratory data analytics (EDA): Normally, in this step, you need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. You can also check whether or not there is any skewness in the data and try to mitigate it, as skewed data can cause problems during the model-building phase.

 

Train/Test Data Splitting: In this step, you need to split the data set into training data and testing data in order to check the performance of your models with unseen data. You can use the stratified k-fold cross-validation method at this stage. For this, you need to choose an appropriate k value such that the minority class is correctly represented in the test folds.

 

Model Building or Hyperparameter Tuning: This is the final step, at which you can try different models and fine-tune their hyperparameters until you get the desired level of performance out of the model on the given data set. Ensure that you start with a baseline linear model before going towards ensembles. You should check if you can get a better performance out of the model by using various sampling techniques.

 

Model Evaluation: Evaluate the performance of the models using appropriate evaluation metrics. Note that since the data is imbalanced, it is important to identify which transactions are fraudulent transactions more accurately than identifying non-fraudulent transactions. Choose an appropriate evaluation metric that reflects this business goal.

 

## Business Impact:

After the model has been built and evaluated with the appropriate metrics, you need to demonstrate its potential benefits by performing a cost-benefit analysis which can then be presented to the relevant business stakeholders. 

 

To perform this analysis, you need to compare the costs incurred before and after the model is deployed. Earlier, the bank paid the entire transaction amount to the customer for every fraudulent transaction which accounted for a heavy loss to the bank.

## Output Solution

1) Credit Card Fraud Detection.ipynb includes the Python code file for the data analysis and model building/evaluation
2) Credit Card Fraud Detection PowerPoint summarizes the data analysis and final model building/evaluation and contains the video explanation link.
3) Cost Cost-benefit analysis includes
   
   - Average number of transactions per month
   - Average number of fraudulent transactions per month
   - Average amount per fraudulent transaction
   - The comparison of cost incurred per month by the bank before and after the model deployment.
 

