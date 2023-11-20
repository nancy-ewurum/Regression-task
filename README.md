# House Price Prediction with Linear Regression

## Overview
Using linear regression to develop a model to predict the price of a house
The aim of this regression analysis is to predict house prices using the relevat features present in the dataset. This analysis would provide insights to real estate developers, house buyers,house sellers etc and enable them to conside the features that could potentially influence the price of a house.<br>

In this analysis, we would consider:

- What house feature(s) contributes most to the price of a house?
- To what extend does each of these feature impact the house price?
- How should the results be interpreted in the context of building a house to optimize sale price?

## Dataset

The data used was housing data from King County. The csv file is attached.

## Results

Features like 'bedrooms', 'yr_built', 'zipcode', 'long', and 'sqft_lot15' have negative impacts on house price. Variables like 'bathrooms', 'sqft_living', 'floors', 'waterfront', 'view', 'condition', 'grade', 'sqft_above', 'sqft_basement', 'yr_renovated', 'lat', and 'sqft_living15' contribute positively to house price while some features, like 'sqft_lot', 'sqft_lot15', and 'yr_renovated', have coefficients close to zero which indicate minimal impact to house price.

The size of the house (sqft_living) had the highest correlation with house price and was chosen as the single feature to predict price in this model.![Reg0](https://github.com/nancy-ewurum/Regression-task/assets/21970681/8a420c56-a062-4ab2-ae14-4257a3ad2e00)
Latitude (lat), Waterfront, Grade show the highest contributions to house prices followed by View, Sqft_living, Bathrooms, Floors, Bedrooms which show moderate positive contritbutions to house price.

![Screenshot 2023-11-20 at 12 16 32](https://github.com/nancy-ewurum/Regression-task/assets/21970681/8b2cb1cf-fdb1-4fc7-b083-0af92260e690)



## Conclusions
Based on the model and the analysis of data, these were the recommendations:
As a developer in King County aiming to optimize sale prices, 
- prioritize large-scale construction,
- value the significance of quality building standards, and
- bear in mind the crucial impact of location
