# Titanic_Survival_Prediciton

The Titanic dataset contains information about the passengers on the Titanic and whether they survived or not. It is commonly used for classification tasks in machine learning. The goal is to predict whether a passenger survived based on features such as age, gender, class, and other characteristics.

Total Rows: 418
Total Columns: 12
Target Variable: Survived (1 = Survived, 0 = Not Survived)

Feature	         Description	                                                         Type
PassengerId	     Unique ID assigned to each passenger	                                 Numerical
Pclass	         Passenger class (1st, 2nd, 3rd)	                                     Categorical
Name	           Passenger’s name	                                                     Text
Sex	             Gender (Male/Female)	                                                 Categorical
Age	             Passenger's age (in years)	                                           Numerical
SibSp	           Number of siblings/spouses aboard	                                   Numerical
Parch	           Number of parents/children aboard	                                   Numerical
Ticket	         Ticket number	                                                       Text
Fare	           Price of the ticket	                                                 Numerical
Cabin	           Cabin number (if available)	                                         Categorical
Embarked	       Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)	 Categorical

Data Preprocessing
1. Handled missing value in Age,Cabin and Fare by MEAN IMPUTAION, dropping the Cabin column since there were 327 missing values.
2. Converted categorical variables: (Sex,Embarked) into numerical format
3. Normalized the Age and Fare column

Data Visulization
1. Count of people survived/not survived.
2. Count of Male and Female Passengers.
3. Count of people survived as per Pclass.
4. Count of people survived as per SibSp.
5. Count of Age of passengers.
6. Pairplot of all the features.

Machine Learning Approach
Train different classification models
   1. Random Forest Classifier
   2. Logistic Regression
Evaluate these models using classification report: accuracy,precision,recall and f1- score

