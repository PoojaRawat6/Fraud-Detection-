
# Online Fraud Detection with Machine Learning and Exploratory Data Analysis (EDA)

This project aims to identify online payment fraud using machine learning techniques. The dataset used for this project contains various features related to online transactions, and our goal is to build a model that can accurately classify transactions as fraudulent or non-fraudulent


## Dataset Description

This dataset is taken from Kaggle. The dataset includes the following columns:

- step: Represents a unit of time where 1 step equals 1 hour.
- type: Type of online transaction (e.g., CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT).
- amount: The amount of the transaction.
- nameOrig: Customer starting the transaction.
- oldbalanceOrg: Balance before the transaction.
- newbalanceOrig: Balance after the transaction.
- nameDest: Recipient of the transaction.
- oldbalanceDest: Initial balance of the recipient before the transaction.
- newbalanceDest: The new balance of the recipient after the transaction.
- isFraud: Indicates whether the transaction is fraudulent (1) or not (0).


## Project Workflow

1. Exploratory Data Analysis (EDA):

- Conducted detailed EDA to understand the distribution and relationships of the data.
- Visualized data using various plots to detect patterns and anomalies.

2. Data Preprocessing:

- Handled missing values and outliers using techniques like quantile-based flooring and capping.
- Encoded categorical variables and normalized numerical features.

3. Correlation Analysis:

- Analyzed correlations between features to understand their relationships.
- Plotted heatmaps to visualize correlation values.

4. Model Training:

Trained a machine learning model to classify transactions as fraudulent or non-fraudulent.
Achieved a high accuracy of 99.9%.


## Conclusion

This project demonstrates the process of identifying online payment fraud using machine learning. By carefully analyzing and preprocessing the data, and then training a robust model, we can accurately detect fraudulent transactions. This work can be further improved and adapted to real-world applications for enhancing the security of online payment systems