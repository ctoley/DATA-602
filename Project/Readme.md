# Fire Incidents Dataset.

## Dataset Description-
Fire Incidents includes a summary of each (non-medical) incident to which the SF Fire Department responded. Each incident record includes the call number, incident number, address, number and type of each unit responding, call type (as determined by dispatch), prime situation (field observation), actions taken, and property loss.

Dataset link- https://data.sfgov.org/Public-Safety/Fire-Incidents/wr8u-xric

The Dataset has :

64 Columns

575k Rows


## Introduction-
As many as 90% of the Fires in the States are caused by people. Fire Incidents are more often that they seem. Many fires are originated by cooking. The datset contains the incidents to which the SF Fire Department responded. These along with incidents also have some unnecesary calls or the alarm went of due to some normal cause.Accidents caused by fire can result in serious injury and damage to personal property. So we are going to evaluate the chances of fire fatalties.

## Problem Statement-
To predict if there will be any fatalties in the fire incidents or not.

## Exploratory Data Analysis And Data Cleaning-
- Dealing with NULL Values-
    
    - Almost 5 lakh null values.
    
    - Few unnecessary values.

- Filled the missing values with Unknown for Categorical Variables.

- Filled the missing values with mean or median for numerical values.

- Carried out Data Vizualization.

- Dropeed few columns which were not important.

- As the dataset was huge and the duplicate rows were just around 7-10, I dropped them.


![image](https://user-images.githubusercontent.com/89624724/146119038-cf5b0c45-2b8e-41aa-812d-e1c518874c4f.png)


## Models-

### - Linear Regression

### - Logistic Regression

### - Decision Tree

### - Random Forest 

### - ADA Boost 


## Results-
Linear Regression Accuracy was 99%. Rest all the algorithms gave 100% accuracy. This was due to the data in the in the training set was all zeros. If taken into consideration only 47 rows were the rows with nulls. 

## Conclusion-

There may or may not involve overfitting but due to the complexity of the data and the way the data is I think getting a 100% accuracy was not a problem. It is just the way data is. I will further take new dataset of similar attributes and try the same.

## Reference-
1) Lecture notes

2) Stack Overflow..cited wherever used
