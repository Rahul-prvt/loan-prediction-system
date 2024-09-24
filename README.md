Loan Prediction System

Project Overview
The Loan Prediction System project aims to assist financial institutions in efficiently and accurately predicting the creditworthiness of loan applicants. Using machine learning techniques, the system analyzes various features such as income, credit history, and employment status to determine loan approval likelihood.

Dataset Description
The dataset used for this project includes the following columns:

Loan_ID: Unique identifier for each loan application.
Gender: Applicant's gender (Male/Female).
Married: Marital status (Yes/No).
Dependents: Number of dependents.
Education: Applicant's educational background.
Self_Employed: Employment status (Yes/No).
ApplicantIncome: Applicant's income.
CoapplicantIncome: Co-applicant's income, if any.
LoanAmount: Requested loan amount.
Loan_Amount_Term: Loan term in months.
Credit_History: Applicant's credit history.
Property_Area: The area where the property is located (Urban/Semiurban/Rural).
Loan_Status: Loan approval status (Y = Approved, N = Not Approved).
Purpose of the Project
The main goal of this project is to:

Develop a predictive model to evaluate loan applications accurately.
Automate the loan approval process using machine learning.
Minimize the risk of loan defaults while promoting financial inclusion.
Steps Included

Removing Duplicates: Ensuring the dataset is free from duplicate records.
Standardizing Data: Ensuring consistency across the dataset, including handling missing data.
Removing Unwanted Columns: Dropping columns not required for the prediction process.
Data Preprocessing: Handling missing values, encoding categorical data, and scaling numerical data.
Model Development: Training models using algorithms like Random Forest, Decision Tree, and Logistic Regression.
Performance Evaluation: Evaluating models using accuracy, precision, recall, and confusion matrix.
Model Selection: Random Forest was chosen for its superior accuracy of 77.92%.
Model Deployment: Saving the model using the Pickle library and deploying it for real-time loan predictions.
Conclusion
The Loan Prediction System effectively reduces the manual workload involved in loan approvals by automating predictions based on historical data. The system achieved a good balance of precision and recall, with a high recall of 97.0%. This ensures that most loan applications likely to be approved are correctly predicted, supporting both financial risk management and inclusion efforts in lending practices.
