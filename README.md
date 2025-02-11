# Gambling_Transaction_Detection
This project focuses on building a machine learning model to detect gambling-related transactions in a dataset of customer transactions. It uses synthetic transaction data containing features such as transaction amounts, merchant information, customer demographics (age, income), and transaction categories.

**Features Used:**
Transaction ID: Unique identifier for each transaction.
Customer ID: Unique identifier for each customer.
Amount: The monetary value of the transaction.
Category: Type of transaction (e.g., Gambling, Shopping, Utilities).
Merchant: Name of the merchant or platform.
Date: Date of the transaction.
Income: Customer’s annual income.
Age: Customer’s age.
Target Variable:
Is Gambling: Binary classification of whether the transaction is gambling-related (1) or not (0).


**Key Techniques Used:**

*Random Forest Classifier: A robust classifier used for initial model training.

*Hyperparameter Tuning: Tuning the models using RandomizedSearchCV to optimize performance.

*Threshold Adjustment: Adjusting classification thresholds to improve recall for gambling transactions.

*Evaluation Metrics: Accuracy, Precision-Recall AUC, ROC-AUC, and F1-Score to evaluate model performance, particularly for imbalanced datasets.
