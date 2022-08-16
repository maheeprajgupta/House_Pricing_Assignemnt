House Pricing Project 

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents

* Checkpoint 1 : Reading and Understanding the Data
* Checkpoint 2 : Reformatting and Cleaning the data (for effective visualisation)
* Feature engineering (using Derived Variables) demonstration (examples only)
* Checkpoint 3: Visualising the Data (EDA)
* Checkpoint 4: Data Preparation for Model Building
* Checkpoint 5: Splitting the Data into Training and Testing Sets
* Checkpoint 6: Shortlisting predictors through Recursive Feature Elimination
* Checkpoint 7: Building a Linear Regression Model
* Checkpoint 8: Regularisation (Hyperparameter Tuning)
* Checkpoint 9: Model Evaluation
* Checkpoint 10: Conclusions

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The business goal is to understand how exactly the prices vary with the variables and to manipulate the management to understand the pricing dynamics of a new market.

## Conclusions
Though the r2_scores are approximately same for both of them, but Lasso will penalize more on the dataset and can also help in feature elimination by making coefficients of lesser significant predictors equal to zero.

So, we will consider the Lasso as our final model.

The top 5 most significant feature variables are:

    1. BsmtFullBath
    2. LotFrontage
    3. OverallQual_10
    4. LowQualFinSF
    5. GarageQual 


All these features have positive coefficients, which means an incease in their value leads to a significant increase in SalePrice (target-variable)


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Statsmodels
- Sklearn

## Contact
Created by [@maheeprajgupta] - feel free to contact me!

