## Dataset Description.
The dataset is of different flight. The dataset has 25 Columns. For the sake of prediction, arr_delay is an important column. Few columns that are repetitive or not important can be dropped.

## Problem Statement
Analyze the data and create a processing pipeline. We are interested if we can predict whether a flight gets delayed or not (arr_delay).

Fit a logistic regression, decision tree, and SVM using grid search. Discuss the performance of each model.

Fit an ensemble using the three above models. Does this improvement performance?

Fit a model using AdaBoost. Does this improve performance?

## Flow Of Analysis
•	EDA(There were missing values which were dealt with. Histograms was used to explain the data in a pictorial way.)

•	Splitting of Training and test datasets

• Creation of Pipeline

• Pipeline for Logistic Regression, Decision Tree and SVM

• Comparision of the scores 

• Ensemble Learning

## Conclusion
SSM performed better as compared to other model but it took a lot of time to run and hence Logistic regression would be preferred.
ADABoost gave almost 9% more accuracy.
