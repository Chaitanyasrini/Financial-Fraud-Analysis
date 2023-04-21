# Financial-Fraud-Analysis

In today's dynamic business landscape, financial fraud has become a persistent and evolving threat that can inflict severe damage to organizations of all sizes. From embezzlement and insider trading to identity theft and cybercrime, financial fraud comes in various forms and can devastate a company's reputation, finances, and operations.

A company’s ability to recognize fraudulent transactions is very important so that
customers are not charged unduly. The accompanying dataset contains transactions
made by credit cards in two days. 

It contains only numeric input variables which are the
result of a Principal Component Analysis (PCA) transformation, due to confidentiality
issues. The only features that are not transformed are 'Time' and 'Dollar_amount'.
● Features P1, P2, ... P28 are the principal components obtained with PCA
● ‘Time' is the seconds elapsed between each transaction and the first transaction
in the dataset.
● 'Dollar_amount' is the transaction amount
Outcome' is the response variable, 1 in case of fraud and 0 otherwise.

This project focuses on the implementing logistic regression and random forest machine learning algorithm and also solves the class imbalance problem through SMOTE (Simplified Minority Over Sampling Technique)
