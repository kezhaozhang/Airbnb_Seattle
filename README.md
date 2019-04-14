# Airbnb in Seattle: What Can be Learned from Data

## Motivation

The project uses Kaggle Airbnb data in Seattle to investigate the key factors that affect the listing availability, guest ratings and listing prices. The result can be used as guidance for Airbnb hosts to improve their business.

## Methods
Exploratory data analysis as well as gradient boosting machine regression models are used to identify the key factors and their effect on the predicted variables. Permutation importance method is used for feature importance; Partial dependence plot is used to characterize feature's marginal effect on the predicted variables.

## Summary of Result
Guests rating is high when they preceive the listings have value. Value is not determined by low price, rather it is a combination of the characteristics of property, host, neighborhood and amenities.

The price of Aribnb listings is mainly determined by the property size, neighborhood and season of the year.

There are opportunities for Airbnb hosts to improve their business by optimizing listings with season, neighborhood and amenities.

## Python Libraries used
- numpy
- pandas
- seaborn
- matplotlib
- sklearn
- eli5
- pdpbox

## Files:
- README.md: this file
- airbnb_seattle.ipynb:  IPython notebook for the analysis, modeling and visualization of the Seattle Airbnb data
- calendar.zip: compressed calendar.csv data file
- listing.zip: compressed listings.csv data file
- reviews.zip: compressed reviews.csv data file
