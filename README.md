# Fraud_Detection_in_Credit_Card_Transaction
This code is for detecting fraud transactions using python using 3 machine learning models and we will be using credit dataset from the kaggle.

Description:
            This is my online internship project and I created this code based on other codes and modified the code and dataset according to my requirements. I used 3 ML models and compared the accuracy and effieciency of the 3 models via graphs.

Dataset:
        I took this dataset from kaggle which contains 284315 rows of normal transaction and 492 fraud transaction. Due to the large size I reduced data set size to 4007 rows which contain 3491 normal transaction and 516 fraud transaction.

Context:
The dataset contains credit card transactions made by European cardholders over a period of two days in September 2013. It was collected to investigate how to deal with highly imbalanced datasets, where the vast majority of transactions are non-fraudulent (normal), while only a small fraction are fraudulent.

Features:
The dataset contains 31 features, most of which are anonymized due to privacy and security concerns. The only non-anonymous features are 'Time', representing the seconds elapsed between this transaction and the first transaction in the dataset, and 'Amount', representing the transaction amount.

Target Variable:
The target variable is 'Class', which takes the value 1 in the case of fraud and 0 otherwise. This is the variable that the machine learning models aim to predict.

Imbalanced Nature:
One significant characteristic of this dataset is its severe class imbalance. The majority of transactions are labeled as 0 (non-fraudulent), while a very small portion is labeled as 1 (fraudulent). This poses a challenge for traditional machine learning models, as they might struggle to learn patterns associated with the minority class.
