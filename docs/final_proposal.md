# New York Taxi fare prediction based on the demand

### Introduction
More than 100,000 automobiles are currently on the road in NYC, an increase of 63,000 over the previous several years. Taxi travels, on the other hand,taxi trips have decreased from 11 million to 8.5 million annually while the number of trips in app-based vehicles has climbed from 6 million to 17 million annually. The NYC Yellow Cab company consequently made the decision to focus more on data. In addition, there are apps like Uber, OLA, Lyft, Gett, and others. How do these apps operate? After all, the fixed price is not an arbitrary assumption.

### Dataset 

https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data

####  Data :
1. No of rows - 1048576
2. No of columns - 8


### Features in the dataset

1. pickup_datetime   : datetime64
2. pickup_longitude  : float64
3. pickup_latitude   : float64
4. dropoff_longitude : float64
5. dropoff_latitude  : float64
6. passenger_count   : int64
7. Fare_amount : float64


## Objective :

The goal of this project is to anticipate the cost and length of a ride so that users can choose the best time to begin their commute. Additionally, it can assist drivers in determining which of two potential rides will be more lucrative.


## Machine learning models 

we are going to use models such as 
1. Linear regression
2. Random forest
3. KNN algorithm 

We will determine which method will provide least mean square error and RMSE Value to calculate fare prices

## Future work:

In this work, we provide a New York Taxi Fare Prediction system that uses a number of variables to forecast the Value of Fare Amount from source to destination. I used the 100,000-row, 7-column  Taxi Fare Prediction Dataset from Kaggle for my experiment. I am going to utiliz the Haversine Formula and machine learning models to forecast Value of Fare Amount.

## Reference : 
https://www.kaggle.com/code/abdurraffay00/nyc-taxi-fare-predictor





