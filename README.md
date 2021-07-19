## Titanic_Final_solution


Different variables present in the datasets.
Numerical Features: 

Age, Fare, SibSp and Parch
Categorical Features: 

Sex, Embarked, Survived and Pclass


Alphanumeric Features: 

Ticket and Cabin(Contains both alphabets and the numeric value)


Text Features:

Name



We analyse and visualise the data to see the changes in Survival rates along with sex, class and age.

For preprocessing we deal with the missing values by dropping the unwanted fields and changing the categorical data of sex as male 0 or 1
and using the mean for NAN values in age so reduce the anamolies.

We apply 5 different algorithms namely:

Logistic Regression
Support Vector Machines
Decision Tree Classifier
Random Forest
KNN Neighbors


## Model Evalution
As we evaluate models based on their accuracy levels on the given dataset. It seems that 'Random Forest' and 'Decision Tree' both are giving the same accuracy. So here we can use both of them in this prediction.

## Result
Accuracy of these models comes out to be 86.31 .
