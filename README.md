# Medical-insurance-payout
Data source :#https://www.kaggle.com/datasets/harshsingh2209/medical-insurance-payout

This project uses machine learning techniques to predict medical insurance charges based on demographic and lifestyle features like age, BMI, number of children, smoking status, etc.

Healthcare insurance companies often need to estimate payouts for policyholders based on various risk factors.
This project uses a dataset from Kaggle: Medical Cost Personal Dataset to build a regression model that predicts insurance charges.

# Methodology
Linear regression, decision tree regression and lasso regression models were trained and tested against the test partition of the data

1 interaction term is introduced (BMI X smoker) as well as bmi and age squared. Bmi and age are squared since it is possible that their relationship with someones well being and ,thus, medical insurance payouts
is nonlinear ( health might not degrade lineary with bmi and age).

# Results 

An R squared of 86.4% was reached in the test partition of the data and mean squared error of 20589913
