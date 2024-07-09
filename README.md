# Customer-Churn-Prediction-using-Machine-Learning

**Introduction:**

Customer churn, the phenomenon where customers cease doing business with a company, is a significant concern for banks and financial institutions. Predicting and understanding churn behavior can help banks proactively retain customers and optimize customer satisfaction. Machine learning offers powerful techniques to analyze customer data and predict churn based on various features. This project aims to develop a predictive model that identifies potential churners in a bank's customer base, enabling targeted retention strategies and improving customer retention rates.

**Problem Statement:**

The objective of this project is to build a machine learning model that predicts customer churn in a bank based on historical customer data. Using features such as customer demographics, transaction history, account status, and customer interaction patterns, the model will learn to identify patterns indicative of potential churners.

**Dataset:**

The dataset used for this Project has 28,382 records and has the following variables:

**Demographic information about customers**

•	customer_id - Customer id

•	vintage - Vintage of the customer with the bank in number of days

•	age - Age of customer

•	gender - Gender of customer

•	dependents - Number of dependents

•	occupation - Occupation of the customer

•	city - City of customer (anonymised)

**Customer Bank Relationship**

•	customer_nw_category - Net worth of customer (3:Low 2:Medium 1:High)

•	branch_code - Branch Code for customer account

•	days_since_last_transaction - No of Days Since Last Credit in Last 1 year

**Transactional Information**

•	current_balance - Balance as of today

•	previous_month_end_balance - End of Month Balance of previous month

•	average_monthly_balance_prevQ - Average monthly balances (AMB) in Previous Quarter

•	average_monthly_balance_prevQ2 - Average monthly balances (AMB) in previous to previous quarter

•	current_month_credit - Total Credit Amount current month

•	previous_month_credit - Total Credit Amount previous month

•	current_month_debit - Total Debit Amount current month

•	previous_month_debit - Total Debit Amount previous month

•	current_month_balance - Average Balance of current month

•	previous_month_balance - Average Balance of previous month

•	churn - Average balance of customer falls below minimum balance in the next quarter (1/0)

**Project Description:**

• Performed in-depth exploration of the churn prediction dataset, identifying key patterns and relationships.

• Developed a Logistic Regression model to classify customer churn.

• Performed Cross Validation to improve the model performance

• Employed AUC ROC as evaluation metric.

**Observation:**

•	For debit values, there is a significant difference in the distribution for churn and non churn and it might be turn out to be an important feature

•	For all the balance features the lower values have much higher proportion of churning customers

•	For most frequent vintage values, the churning customers are slightly higher, while for higher values of vintage, we have mostly non churning customers which is in sync with the age variable

•	There is a significant difference for different occupations and certainly would be interesting to use as a feature for prediction of churn.

•	Achieved an ROC AUC Score of 0.79 using the model.

**Skills:** Machine Learning · Exploratory Data Analysis · Logistic Regression · Data Pre-Processing · Cross Validation


