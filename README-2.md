# credit-risk-classification.


The purpose of the following analysis is to predict creditworthiness in borrowers based on historical data from a peer-to-peer lending service. The dataset contains several financial attributes that can help determine whether a borrower will be a credit risk (high-risk loan) or likely to repay the full amount of an installment on time and in good conditions (healthy loan). This study employs a machine learning model known as Logistic Regression to classify loans into high-risk and healthy categories. Credit BlackBox uses this data to evaluate model performance, enabling the company to make informed decisions about lending policies and risk management.


Logistic Regression Model:

Accuracy: 99% - This indicates the percentage of correctly identified loans out of all loans.
Precision:
High-risk loans (1): 86% - This score represents the percentage of high-risk loan predictions that were true.
Healthy Loans (0): 100% - This rate shows how many loans are correctly predicted as healthy, aiming to minimize false positives.
Recall:
For High-Risk Loans (1): 91% - This score tells us how well our model is able to identify actual high-risk loans.
For Healthy Loans (0): 100% - This score reflects how accurately the model identifies truly healthy loans.

For both high-risk and healthy loans, the Logistic Regression model demonstrates excellent accuracy, with a 99% overall accuracy rate. This indicates that the model correctly identifies loans most of the time. The precision and recall scores for high-risk loans—86% and 91%, respectively—suggest that the model is effective in predicting borrowers who are likely to default.

Based on these results, I suggest using this model for credit risk assessment. The high precision and recall for high-risk loans make it a suitable choice for managing lending risk. However, if future evaluations show a need for improvement, the model could be fine-tuned, or alternative models such as Random Forest or Gradient Boosting could be explored for potentially better performance.



 

