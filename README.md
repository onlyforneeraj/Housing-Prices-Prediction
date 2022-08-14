# Project Name : Housing Prices Prediction Project


> Description : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. Requireemnt is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Real estate specially housing is a big financial market. Numbers of players are involved in buying, selling and brokering the houses including public at large. A number of website are available in the internet which provide the approximation on the value of the house depending on the house' features. 

- What is the background of your project?
In an attempt to have a kick start in the Australian market, this project has been developed to provide an estimate for the houses in Australia.

- What is the business problem that your project is trying to solve?
Specifically, company wants to understand the factors affecting the prices of the houses in Australian market. They want to know:
Which variables are significant in predicting the housing prices.
How well those variables describe the variability in housing prices.


- What is the dataset that is being used?
housing_data.csv

## Conclusions
Features advised by the Lasso Regression model explain 87% (R2) of the variability in the price. And SalePrice advised by the model can be $28000 (RMSE) less or more than the actual value.

Optimal value of alpha for Ridge regression: 3

Optimal value of alpha for Lasso regression: 0.1

Conclusion from the most significant attributes:

TotalBsmtSF, 2ndFlrSF, OverallQual, RoofMatl_WdShngl, TotRmsAbvGrd, Neighborhood_NoRidge, Neighborhood_StoneBr, LotArea, OverallCond, GarageCars, Neighborhood_NridgHt, Foundation_Slab, Neighborhood_Crawfor, FullBath, YearBuilt, SaleType_New, BsmtFullBath, LandContour_HLS, KitchenQual, 

## Technologies Used
- Python - version 3.6
- pandas - version 1.1.5
- numpy - version 1.20.3
- matplotlib - version 3.3.4
- seaborn - version 0.11.2
- sklearn - version 0.24.2
- statsmodels - version 0.12.2



## Acknowledgements
- This project is an assigment by Upgrad and IIIT-B as a part of Exploratory Data Analysis


## Contact
Created by [@onlyforneeraj] - feel free to contact me!


License: This project is open source and available under the general use License.
