# credit-risk-classification

# Credit Risk Analysis Report

# Overview
The purpose of this analysis is to assess credit risk using machine learning models. We aim to predict loans to assist banks in making informed decisions and minimizing potential losses.

# Results
Accuracy: 0.99
Precision for 0 (healthy loans): 1.00
Recall for 0 (healthy loans): 1.00
Precision for 1 (high-risk loans): 0.87
Recall for 1 (high-risk loans): 0.89

# Summary
The Logistic Regression model demonstrates strong performance in assessing credit risk. In precision and recall for 0 (healthy loans), it performs at the highest level of 1.00, 100%. In precision for 1 (high-risk loans) it performed at 0.87, 87% and at 0.89, 89% for recall. The model successfully classifies loans with lower risk 100% of the time, and still performs high for predicting high-risk loans, but at 87-89%.

The accuracy of 0.99, 99% is notably high, indicating that the model is accurate in its overall predictions.

The Logistic Regression model is recommended due to its high recall for high-risk cases. The model's high accuracy and well-rounded precision and recall for both high-risk and healthy loans make it a strong candidate for use.

However, it should be noted that the model is not 100% accurate when predicting high-risk loans, and while 88% sounds high in terms of prediction, that also means 12% of the time it is predicting in-accurately, so this is something to take into consideration.
