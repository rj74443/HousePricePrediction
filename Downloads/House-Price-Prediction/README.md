# Advanced Regression-House Price Prediction 
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: 
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.

Using GridSearchCV the model arrives at a final optimum lambda to predict the house prices using ridge and lasso regression.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Advanced linear regression like Ridge & Lasso is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module. 
- We are trying to predict the sale price(target variable) of the houses based on numerous independent(features) values. 
- The house price dataset is being used. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- The R-squared value of final model on train set is 92.4% approx. whereas the test set has a value of 85% approx. which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection & model evaluation on the test set. 

- Concepts such as EDA, VIF & RFE were used and model building was done using statsmodels & scikit-learn library

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@rj74443] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->