# EDA-Project

## Housing market in King County USA

This notebook  is about predicting the housing prices for King County. It contains a data science lyfe cycle  with data cleaning, feature engingeering and model selection and prediction. 

In this repository the file Project EDA.ipynb contains all the code for this project. King_County_Housing_prices_dataset.csv contains the data used for this project. EDA - Project Matthis We.pdf contains a presentation with a short overview of my findings. 

![alt text](https://cache.marriott.com/marriottassets/destinations/hero/seattle-destination.jpg?interpolation=progressive-bilinear&resize=2880:960 "Seattle view")

## Data Cleaning

Many of the data received were in type integer or float. Since many of them were categorical, for each one dummies were created.

## Feature engineering 

One of the most insightful variables in order to compare different houses with each other is the price per square feet.
Another variable which is included is the basement_present. Since there is nearly no correlation between basement size and price I introduced if there is a basement present.
Creating a dashboard with a heatmap and filtering through different variables

## Model selection

Multiple logistic regression with statsmodels.formula. Testing the model was done by train_test_split from Scikit learn.
