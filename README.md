Description:

The goal of this project is to predict the credit score of a user, which represents the user's creditworthiness. The credit scores are labeled with letters from A to G, and classification techniques are used to predict the user's credit score.

The dataset contains various data about users, including their personal and financial information:

The input data used for training the model includes:

person_age - the age of the user

person_income - the user's annual income

person_home_ownership - homeownership status

person_emp_length - length of the user's employment

loan_amnt -  loan amount

loan_int_rate - interest rate on the loan

loan_status - whether the user has had any delays in repaying previous loans

loan_percent_income - the percentage of the user's income required for loan repayment

cb_person_default_on_file - whether the user has had delays in repaying previous loans

cb_person_cred_hist_length - the length of the user's credit history

The machine learning model used for predicting the credit score: Gradient Boosting Classifier

The accuracy of the algorithm on the test dataset is 98.11%.

                precision    recall  f1-score   support

           A       0.99      0.99      0.99      1541
           B       0.98      0.99      0.99      1439
           C       0.98      0.98      0.98       974
           D       0.97      0.95      0.96       514
           E       0.92      0.88      0.90       126
           F       0.88      0.67      0.76        21
           G       0.67      1.00      0.80         2

    accuracy                           0.98      4617
   macro avg:       0.91      0.92      0.91      4617
weighted avg:       0.98      0.98      0.98      4617

