# Surprise Housing - Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 
>The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
>The company wants to know:  
    - Which variables are significant in predicting the price of a house, and  
    - How well those variables describe the price of a house.


## Table of Contents
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Business Goal
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
The variables which are significant in predicting the price of a house are:
- OverallQual_9, OverallQual_10, and OverallQual_8- Indicates the overall material and finish quality of the house. The houses with high quality material and finish have high price. 
- GrLivArea - Indicates the above grade (ground) living area square feet. The houses with large living area have high price.
- Exterior1st_BrkFace - Indicates the exterior covering on house. The houses with brick face have high price. 
- Functional_Typ - Indicates the home functionality. The houses with typical functionality have high price.
- OverallCond_9 - Indicates the overall condition of the house. The houses with excellent condition have high price.
- Neighborhood_StoneBr, Neighborhood_NridgHt, Neighborhood_Crawfor - Indicates the physical locations of the house. The houses in Stone Brook, Northridge Heights, and Crawford have high price.
- SaleType_New - Indicates the type of sale. The houses with new sale have high price.
- MSZoning_FV - Indicates the general zoning classification of the sale. The houses with floating village residential zoning have high price.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.10.10
- Numpy - version 1.24.2
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This case study is part of the course Executive PG Programme in Machine Learning and Artificial Intelligence offered by UpGrad.
- The dataset is provided by UpGrad.


## Contact
Created by @robinsonrajan and @mikenextml - feel free to contact me!
