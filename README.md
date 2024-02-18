# credit-risk-classification

In this analysis we are trying to show the performance of machine learning models in trying to predict credit risk.
The data is about loan aplicants. Target  varoble is "loan_status" , indicating whether a loan is high-risk (1) or healthy (0).
WE are using  two models for evaluation :a Logistic Regression model with the original data and a Logistic Regression model with resampled training data.

Results
Logistic Regression Model with Original Data:
Accuracy Score: 0.99
Precision (label 0 - healthy loan): 1.00
Recall (label 0 - healthy loan): 0.99
Precision (label 1 - high-risk loan): 0.86
Recall (label 1 - high-risk loan): 0.94

Logistic Regression Model with Resampled Data:
Accuracy Score: 0.99
Precision (label 0 - healthy loan): 1.00
Recall (label 0 - healthy loan): 0.99
Precision (label 1 - high-risk loan): 0.85
Recall (label 1 - high-risk loan): 0.99

Both models demostrate great performance with hight accuracy.
I would recomend the Logistic Regression model due to more balanced performance .
