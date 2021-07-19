## Titanic_Final_solution


## Different variables present in the datasets:


## Numerical Features: 
Age, Fare, SibSp and Parch


## Categorical Features: 
Sex, Embarked, Survived and Pclass


## Alphanumeric Features: 
Ticket and Cabin(Contains both alphabets and the numeric value)


##  Text Features:
Name


## Analysing and visualising the data

We analyse and visualise the data to see the changes in Survival rates along with sex, class and age.


## Pre Processing

For preprocessing ,
we deal with the missing values by dropping the unwanted fields
changing the categorical data of sex as male 0 or 1(Hot encoding technique),
Changing embarked with the most common value and using the mean for NAN values in age inorder to reduce the anamolies.


## We apply 5 different algorithms namely:

1.Logistic Regression

2.Support Vector Machines

3.Decision Tree Classifier 

4.Random Forest

5.KNN Neighbors


## Model Evaluation
As we evaluate models based on their accuracy levels on the given dataset. 'Random Forest' and 'Decision Tree' both are giving the same accuracy. So, we can use both of them in this prediction.

## Result
Accuracy of these models comes out to be 86.31 .


## Codacy B
