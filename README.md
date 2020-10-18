# HR-Promotion-Prediction
about data:
This is a WNS Analytics Wizard competition.<br>
The Goal is to develop a classification model to predict whether an employee is promoted or not, and also understand the factors that lead to this promotion.<br>
The data-set consists of 54808 rows where each row had 14 attributes including target variable (i.e “is_promoted”).<br>
### Problem statement:
- we have given past employee data like department , education , training and its score , previous year rating , promotion etc..as training data and we needed to predict promotion probabilities for test data.
### Challenge:
- After some analysis we found out that the main challenge was the imbalance class in target prediction.
- Since the class is imbalance leader board was measured in F1 score rather then accuracy (If we predict all as not promoted then we will have accuracy more then 90% which is a wrong metric to measure).
### Solution and Approach
- Data Cleaning: There was some missing values like in education field
- EDA:
The Algorithm: After exploring many classifiers, I finally decided to concentrate on boosting algorithm XGboost which can be used for imbalance classes, and he gaves me a good F1-Score.

