
# Project Name
> House Price Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company wants to know, Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.Also,to determine the optimal value of lambda for ridge and lasso regression

## Technologies Used
- library - pandas
- library - numpy
- library - sklearn
- library - seaborn

Using python programming in Jupyter notebook following steps has been adopted.
- Data Inspection
- EDA
- Missing Value Imputation
- Scaling
- Train and Test data 
- Modeling
- Model evaluation

## Conclusions
we got a decent score for both Ridge and Lasso regression.
        - Ridge : Train :90.92 Test :87.45
        - Lasso : Train :89.83 Test :86.47
   - Top 5 most significant variables in Ridge are:
       - ('SaleCondition_Partial', 0.122)
       - ('SaleCondition_Others', 0.112)
       - ('SaleCondition_Normal', 0.102)
       - ('GarageFinish_Unf', 0.078)
       - ('GarageFinish_RFn', 0.075)
   - Top 5 most significant variables in Lasso are:
       - ('SaleCondition_Partial', 0.124)
       - ('SaleCondition_Others', 0.115)
       - ('SaleCondition_Normal', 0.114)
       - ('GarageFinish_Unf', 0.066)
       - ('GarageFinish_RFn', 0.062)
   - These Varaiables are directly proportional to each other.
   - Optimal Value of lamda for ridge : 10
   - Optimal Value of lamda for Lasso : 0.001
    -Because of Feature selection as well we can choose Lasso regression in this case.

## Acknowledgements
This project is based on Advanced Regression Assignment.
This is created by Shubhashree P.


