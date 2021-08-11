# MACHINE_LEARNING <br />

***Machine learning is a branch of artificial intelligence (AI) and computer science which focuses on the use of data and algorithms to imitate the way that humans learn, gradually improving its accuracy***

## *SUPERVISED MACHINE_LEARNING* <br />

***Supervised Learning is a type of machine learning used to train models from labeled training data. It allows you to predict output for future or unseen data*** <br />

### Types of supervised learning algorithms<br />
 - REGRESSION 
 - CLASSIFICATION
### Regression types:<br />
                    1. LINEAR_REGRESSION
                    2. MULTIPLE_LINEAR_REGRESSION
                    3. POLYNOMIAL_REGRESSION
 #### LINEAR_REGRESSION,<br />
 Linear Regression is a statistical model used to predict the relationship between independent and 
dependent variables denoted by x and y respectively
* **Examine 2 factors** <br />
1. How closely are x and y related ?
Linear regression gives a number
between -1 and 1 indicating
the strength of correlation 
between the two variables
0 : no correlation 
1 : positively correlated 
-1 : negatively correlated

2. Prediction
When the relationship between x 
and y is known, use this to predict 
future values of y for a value of x 
This is done by fitting a regression 
line and represented by a linear equation:
#### y = a * x + b

#### simple linear regression example click here  - [linear_regression](https://github.com/Arun998/MACHINE-LEARNING/blob/main/simplelinearregression.ipynb) <br />
#### MULTIPLE LINEAR REGRESSION <br/>
Multiple linear regression is a statistical technique used to predict the outcome of a response variable <br/>
through several explanatory variables and model the relationships between them.<br/>

***Equation for MLR***<br/>
#### Y = m1* x1 + m2* x2 + m3* x3 + ………+ mn* xn + c <br/>
***BASTON HOUSEPRICE PREDICTION USING MLR*** -[multiple linear regression](https://github.com/Arun998/MACHINE-LEARNING/blob/main/Boston%20House%20Price%20%20Prediction.ipynb)<br/>

## Accuracy Metrics <br/>
### *R-square  is the most common metric to judge the 
performance of regression models<br/>
Error = Predicted Value-ActualValue<br/>
Example: Performing linear regression on sq. Area (x) and Price (y) returns R-square value as 16 
This means you have 16% information to make an accurate prediction about the price.<br/>
lies between 0 -100 %<br/>

### Adjusted R-Square <br/>
##### Adjusted R^2=1-(1-R^2)(N-1)/N-P-1 <br/>
It penalizes the attribute that are not correlated<br/>
As we increase the no of independent N-P-1 becomes small number attribute increases adjust r^2 decreases when an attribute not correlated with target that time only adjusted R^2 decreases


## CLASSIFICATION <br/>
If the target variable is categorical then we use classification<br/>
 #####  LogisticRegression <br/>
 Logisticregression is widely used to predict the binary outcomes for given set of independent variables<br/>
   *The dependent variable can have only two values such as 0 or 1, win or loose, pass or fail*<br/>
 *** Use_cases ***<br/>
    loan_sanction,spamfiltering exam_result i.e pass or fail <br/>
The probability of distribution of output is restricted to 1 or 0<br/>
###### Logisticregression equation is sigmoid function i.e s(t)=1/1+e^-t <br/>

t->represents data volume<br/>
s(t)->represent the probability<br/>
s-> shaped curve<br/>
Iris Flower data clsssification using Logistic regression -[LogisticRegression](https://github.com/Arun998/MACHINE-LEARNING/blob/main/CLASSIFICATION(IRIS%20FLOWER%20).ipynb)



