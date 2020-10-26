### Loan Prediction Model
A small tutorial given at LA DataCon on a basic Data Science. The tutorial was done in python but I wanted to try to do it in R.

What happened and why it happened is what Data Analysis amounts to. <br>
What will happen tomorrow is predictive analytics.

#### *Case Problem: A bank wants to determine who should get a loan based on current data.*

1. Understand the problem and what the expected product is:
A bank wants to determine which customers are most likely to need a bank loan. Using data on hand:
  the final product should be a predictive model that can determine if a new client needs a loan.

2. What data do we have?
The data consists of generale features a financial institution would have on its clients. *(Ex. Loan amount, Gender, Education,etc)*
Dataset is mixed with both numeric and categorical data.

3. Analysis and Preparation
 - Initial summary showed missing values in several columns of the dataset.
 - These missing values were replaced with either the mean for numeric or the mode for categorical data.
 - One hot encoding was used on categorical variables.
 - A correlation matrix was used to determine which features had the highest correlation.
 
4. Model Selction
 - Logistic Regression
 - Decision Tree
 
5. Results

 * Decision Tree
   
|Accuracy   | Precision   |  Sensitivity  | Specificity  | 
|-----------|--------------|---------------|--------------|
| 0.8366013  |  0.9339623 | 0.9339623  | 0.6170213  | 


*References*
- Intro to Data Science, LA DataCon, Zia Khan
