# Bank Churn probability prediction
This project is a part of a Kaggle competition.
- the `submission_file.csv` contains the final probabilities which. The scoring is automatic and done by Kaggle (score = 0,87 out of 1)
- `1train_sampled.csv` contains sampled data of a training dataset. This file is used for creating visualisations in `Dashboard Churn Data Visualization.html`
- `Dashboard Churn Data Visualization.html` is a dashboard with data visualisations

The dataset contains information about bank customers and their banking activities. It includes features such as customer demographics, banking products, transactions, and customer behavior. The goal is to predict whether a customer will churn (leave the bank) or not based on the provided features.

Column Description
Customer ID: A unique identifier for each customer
Surname: The customer's surname or last name
Credit Score: A numerical value representing the customer's credit score
Geography: The country where the customer resides (France, Spain, or Germany)
Gender: The customer's gender (Male or Female)
Age: The customer's age
Tenure: The number of years the customer has been with the bank
Balance: The customer's account balance
NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
EstimatedSalary: The estimated salary of the customer
Exited: Whether the customer has churned (1 = yes, 0 = no)
