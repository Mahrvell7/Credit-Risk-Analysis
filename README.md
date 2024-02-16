
## Credit Risk Analysis
Welcome to the Credit Risk Analysis Project repository! This project aims to analyze credit risk using machine learning algorithms and predictive modeling techniques.

# Overview
In this project, we analyze a dataset containing information about individuals applying for loans. The goal is to build machine learning models to predict credit risk and identify potential default cases. We explore various algorithms including logistic regression, Random Forest, Gradient Boosting, and XGBoost to achieve this objective.

# Feature Descriptions
person_age: Age of the individual applying for the loan.

person_income: Annual income of the individual.

person_home_ownership: Type of home ownership of the individual.

rent: The individual is currently renting a property.

mortgage: The individual has a mortgage on the property they own.

own: The individual owns their home outright.

other: Other categories of home ownership that may be specific to the dataset.

person_emp_length: Employment length of the individual in years.

loan_intent: The intent behind the loan application.

loan_grade: The grade assigned to the loan based on the creditworthiness of the borrower.

    A: The borrower has a high creditworthiness, indicating low risk.
    B: The borrower is relatively low-risk, but not as creditworthy as Grade A.
    C: The borrower's creditworthiness is moderate.
    D: The borrower is considered to have higher risk compared to previous grades.
    E: The borrower's creditworthiness is lower, indicating a higher risk.
    F: The borrower poses a significant credit risk.
    G: The borrower's creditworthiness is the lowest, signifying the highest risk.
loan_amnt: The loan amount requested by the individual.

loan_int_rate: The interest rate associated with the loan.

loan_status: Loan status, where 0 indicates non-default and 1 indicates default.
   
    0: Non-default - The borrower successfully repaid the loan as agreed, and there was no default.
   
    1: Default - The borrower failed to repay the loan according to the agreed-upon terms and defaulted on the loan.

loan_percent_income: The percentage of income represented by the loan amount.

cb_person_default_on_file: Historical default of the individual as per credit bureau records.
   
    Y: The individual has a history of defaults on their credit file.
   
    N: The individual does not have any history of defaults.

cb_preson_cred_hist_length: The length of credit history for the individual.


# Machine Learing Models used:
1. logistic regression
2. RandomForest Classifier
3. Gradient Boosting classifier
4. XGBoost (Extreme Gradient Boosting Classifier)

   # Model accurracy
Accuracy (Logistic Regression - Default): 0.8623599815866196

Accuracy (Random Forest - Default): 0.9288015958263004

Accuracy (Gradient Boosting - Default): 0.9206690194874942

Accuracy (XGBoost - Default): 0.9341721651066441

Based on these results, XGBoost achieved the highest accuracy among the models without hyperparameter tuning.
