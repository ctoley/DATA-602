# Dataset Description 

The dataset hast whether or not the lady has diabetes.  There are various constraints that are taken into consideration like
 Pregnancies (number of times pregnant),
 Oral glucose tolerance test 
 Blood Pressure (Diastolic Blood Pressure in mmHg),
 Skin Thickness (Triceps skin fold thickness in mm),
 Insulin (2 h serum insulin in mu U/ml),
 BMI (Body Mass Index in kg/m2),
 Age (years),
 Pedigree Diabetes Function

# Problem Statement
to run a Logistic Regression model with grid search cross-validation using 10 folds. Search 5 different regularization strengths and 2 solvers. What is the best model? How does it perform on the test set?

# Solution
Creating a pipeline for feature processing. Splitting the dataset by train_test_split. Carrying our Logistic regression with Grid search cross-validation using 10 folds.
The accuracy is almost the same for training and test. The metric used is Precision and Recall. Also, the model with No-PCA has accuracy 1.00. The precision was 0.97.
Used the Decision tree to check the accuracy of Test and Train Data.


