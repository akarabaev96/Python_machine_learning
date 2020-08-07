# Predicting mobile operator's customers churn using Logistic Regression

## Dataset used
Dataset of Telecom mobile operator containing customers' information, activity and information about whether they churned or didn't

## Goal of the analysis
Predict whether customer will churn or won't

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
- Checking for missing values
- Creating dummies for categorical variables
- Checking and solving multicollinearity issue
- Logarithmizing of independent variables to restrict outliers' influence on results
- Scaling all numerical variables to bring them to unit variance
- Dividing dataset to train and test parts in ratio 80/20
- Initializing Logistic Regression model
- Using k-fold algorithm searching for optimal regularization parameter 'C'
- With optimal C=0.01 accuracy of model on train part is 86%
- Using optimal model predicting whether customer will churn or not on test part

## Results
### Accuracy: 87.8%
### Precision: 88.6%
### Recall: 98.8%

- Accuracy of the model is 87.8%, which is quite high and consistent with the accuracy obtained during training, so we can say that during training there weren't overfitting and underfitting. 
- Precision is 88.6%, which means that out of all customers labeled as churn ones 88.6% of them really churned.
- Recall is 98.8%, which shows that out of all customers that churned our model will detect 98.8% of them
