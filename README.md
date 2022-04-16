# Master_LJMU-IIITB_Course03_02
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Problem Statement
BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## Solution proposed: 
We create a Linear Regression Model to Predict the future sales considering the various factors provided.

## Conclusions
We were able to build a linear regression model with R-squared 85.52% and  Adjusted R-squared 83.70%

Final model: cnt = 1484.6491415659893 + (2037.54696607yr) + (-841.03748787holiday) + (3846.07337739temp) + (-766.67098899windspeed) + (-923.48342301season_spring) + (408.51396001season_winter) + (307.70077276mnth_mar) + (269.64824028mnth_sept) + (315.81333325weekday_sat) + (-1732.54434116weathersit_Snow) + (734.20406371weathersit_clear) + (-883.39495721temp_cat_hot) + (414.30718619temp_cat_normal) + (-246.44787831temp_cat_very_cold) + (-3274.04150401temp_cat_very_hot) + (-1926.57743793windspeed_cat_strong_breeze)

Temprature and Windspeed, and Year is highly correlated to demand.

The model is low colinearity, since most of attribute have VIF under 5.0, only temp and winspeed is 7.48 and 5.9, respectively.

## Libraries
Pandas
Statsmodels
Sklearn
Seaborn

## Author
Created by Phuc Thanh Nguyen - no lisence of this notebook so feel free to use.