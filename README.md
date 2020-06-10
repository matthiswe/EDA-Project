# EDA-Project

## Housing market in King County USA

This notebook  is about predicting the housing prices for King County. It contains a data science lyfe cycle  with data cleaning, feature engingeering and model selection and prediction. 


[logo]:https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.marriott.de%2Fhotel-search%2Fseattle.hotels.washington.united-states.travel%2F&psig=AOvVaw0Uz07bIVYi0GhkDHaUGQ2g&ust=1591871647634000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJC6rbaG9-kCFQAAAAAdAAAAABAD

## Data Cleaning

Many of the data received were in type integer or float. Since many of them were categorical, for each one dummies were created.

## Feature engineering 

One of the most insightful variables in order to compare different houses with each other is the price per square feet.
Another variable which is included is the basement_present. Since there is nearly no correlation between basement size and price I introduced if there is a basement present.
Creating a dashboard with a heatmap and filtering through different variables

## Model selection

Multiple logistic regression with statsmodels.formula. Testing the model was done by train_test_split from Scikit learn.