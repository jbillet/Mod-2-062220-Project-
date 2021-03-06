# NYC AirBnb Price Predictions

## Introduction:

For this project, I picked a data set of 48,000 Airbnb listings in New York City from Kaggle. Throughout this project, I utilized that data set to predict the continuouis variable: Price.

## Objective:

The objective of this project was to take a look at multiple features including, but not limited to: Minimum Nights Stayed, Neighborhood Groups (Boroughs), Neighborhoods, Room Type, and Reviews to see how these independent variables impact the target variable: Price. 

## The Dataset:

Kaggle was utilized in sourcing this dataset.

## Skills Required:

The skills used to complete this project consisted of working with Python to make visualizations using Pandas and cleaning the data set well. Also understanding & knowing how to interpret various regression models based on feature engineering & selection.

## Questions Asked:

Is there a correlation between Price & Room Type? Is there a correlation between Price & Neighborhood Group (Boroughs)? What is the relationship between Room Type and Neighborhoods? Which features can I add to this dataset to enhance my model? Which features can I utilize during modeling to enhance my model?

## How I Organized The Data:

After gathering a dataset of roughly 48,000 AIrbnb listings from Kaggle, I cleaned it, and chose the features I thought would correlate the strongest to the price of an Airbnb.

Following data cleaning and feature selection, I performed EDA and decided which features to keep in the models being used. I then split the data into training and testing and analyzed the different values of the R^2 and RMSE for each model (OLS, Lasso).

In the end, I compared the differnet models to see which can predict the best price of an Airbnb.


## Future Steps:

In the future, I would like to: 

1. Find additional data sets to merge with
2. Investigate amount of bedrooms vs Price
3. Seek competitive analysis with Sonder
4. Expand landmark data engineering
5. Integrate subway station coordinates  

Adding these features will enhance the overall model as there will be a greater understanding, as well as a broader range of featres to predict a model.  


## Analysis Recommendation:

In conclusion, I can suggest that the type of room is the most statistically significant feature in determining the price of an Airbnb in New York City. The OLS model with the feature "distance from Times Square to the Airbnb"  is best represented to predict pricing at a New York City Airbnb. 

## Presentation Link:


```python
https://docs.google.com/presentation/d/1xGW9cS4XVV_HdIq0096Q7PJ-u-a63lQQ419e4Lx0Ibo/edit?usp=sharing
```
