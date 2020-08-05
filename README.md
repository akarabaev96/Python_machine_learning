# Telecom churn dataset

Dataset of Telecom mobile operator containing customers' information, activity and information about whether they churned or didn't

## Goal of the analysis
Predict whether customer will churn or will not

## Information used in the prediction
- Customer's state of residence
- International plan 
- Voice mail plan
- Number vmail messages
- Total day minutes
- Total day calls
- Total day charge
- Total evening minutes
- Total evening calls
- Total evening charge
- Total night minutes
- Total night calls
- Total night charge
- Total international minutes
- Total international calls
- Total international charge
- Customer service calls 
- Churn status

## Steps performed:
- Creating dummies for categorical variables
- Scaling all numerical variables to bring them to unit variance
- Dividing dataset to train and test parts in ratio 80/20
- Initializing Logistic Regression model
- Using k-fold algorithm searching for optimal regularization parameter 'C'
- With optimal C=0.01 accuracy of model on train part is 86%
- Using optimal model predicting whether customer will churn or not on test part

## Results
