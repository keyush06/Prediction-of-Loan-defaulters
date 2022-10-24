# Prediction-of-Loan-defaulters

* In this project, we predict the loan defaulters by considering a data 6000 loan applicants with a range of 15 features. It is up to us to determine whether the applicant is likely to default on his/her loan, based on the attributes provided to us for each applicant.

* The main aim of this project is to successfully predict the defaulters, according to “default” column which has two values 'yes' and 'no' for default.

* Firstly, We will do some exploratory data analysis and just see what the dataset looks like. This will give us an overview of the no of datapoints, attributes, datatypes, general description, etc.

* ##### Then we use  WOE & IV for selecting the most important variables. The weight of evidence tells the predictive power of an independent variable in relation to the dependent variable. Since it evolved from credit scoring world, it is generally described as a measure of the separation of good and bad customers. "Bad Customers" refers to the customers who defaulted on a loan. and "Good Customers" refers to the customers who paid back loan. Positive WOE means Distribution of Goods > Distribution of Bads whereas Negative WOE means Distribution of Goods < Distribution of Bads.

* We then use various ML models in order th attain the most accurate model.

* We also use SMOTE in order tpo tackle an imbalanced data set.
