# Surprise Housing company:
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia..

## Goals of the Case Study
- You are required to model the price of houses with the available independent variables. 
- This model will then be used by the management to understand how exactly the prices vary with the variables.
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
- The model will be a good way for management to understand the pricing dynamics of a new market.
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- And to determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
 - Reading and understanding the data
- Data Visualisation
- Data engineering such as removing null values filling Nan values to                      
- make the data usable for model building
- Data finalisation 
- Data splitting for building the model
- Basic Linear Regression Model using RFE 
- Ridge and Lasso Regression models to regularize the model 
- Residual Analysis of the training data
- Subjective Questions

## Conclusions

- We can see that Lasso model is more better as the r2 scores are very near to each other which means the model is generalizing very good on unseen test data as well.
- The most important features in the model are MSSubClass- Depending on teh type of the building.
BsmtFullBath,
Neighborhood_Crawfor- Depending on the nearby companies,where crawfor is a big company, prices tend to increase as many employees would prefer houses near their houses.
,Neighborhood_Somerst-same as above, depending on the company,
OverallCond-Depending on the overall condition of the house. etc.
,Neighborhood_NridgHt,Condition1_Norm,YearRemodAdd,
MSZoning_RL
Optimal values of Ridge and Lasso are 0.6 and 0.0012

## Technologies Used
- NumPy version: 1.20.3 
- Pandas version: 1.3.4 
- Seaborn version: 0.11.2'
- Sklearn
- Statsmodels
- matplotlib

- Due to more number of variables in the dataset , the visualization graphs might take a while to load on github,downloading the jupyter code file will eradicate the problem.

## Contact
Created by [@Rajeshdraksharapu] - feel free to contact me!



