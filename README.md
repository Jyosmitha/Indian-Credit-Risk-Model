# Indian-Credit-Risk-Model
Finance and Risk Analytics

You are requested to create an India credit risk(default) model, using the data provided in the spreadsheet raw-data.xlsx, and validate it on validation_data.xlsx. Please use the logistic regression framework to develop the credit default model.

 

Hints :

Data description - Please direct them to the video - Default Risk Prediction. After removing variables for multicollinearity, we should try to take at least one variable for creating the model from each of the 4 factors namely - 
1) Profitability
2) Leverage
3) Liquidity
4) Company's size
In Dr. Sarkar's video of Default Risk Estimation, he has clearly bifurcated all the variables in different buckets.
Creation of new variables - This is an important step in the project as the company which is the biggest in size, will also have bigger asset size, cash flows etc. (Hint: We need to think in terms of ratios - Equity to asset ratio, debt to equity ratio etc)
Dependent variable - We need to create a default variable which should take the value of 1 when net worth next year is negative & 0 when net worth next year is positive.
Validation Dataset -  We need to build the model on raw dataset and check the model performance measures on validation dataset.
Please find attached the files to be referred. 

Topics

Marks

EDA

40

Outlier Treatment

10

Missing Value Treatment

7.5

New Variables Creation (One ration for profitability, leverage, liquidity and company's size each )

7.5

Check for multicollinearity

7.5

Univariate & bivariate analysis

7.5

 

Modeling

30

Build Logistic Regression Model on most important variables

15

Analyze coefficient & their signs

15

 

Model Performance Measures

20

Predict accuracy of model on dev and validation datasets

10

Sort the data in descending order based on probability of default and then divide into 10 dociles based on probability & check how well the model has performed

10
