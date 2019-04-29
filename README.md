Taxi_Demand_prediction
======================

Problem statement: Given a region and a time, predict number of pickups.

 

Data contains various features like pickup longitude, latitude, drop longitude,
latitude, date-time, passenger_count, trip_distance, fare_amount.

 

Data Preprocessing and preparation

1.  Outliers are removed from all the features

2.  New features like speed are added

3.  The entire city is divided into different regions using K-Means clustering
    algorithm

4.  Time is divided into 10 minute windows.

5.  Data smoothing is performed

6.  Simple moving Averages, Weighted MA, Exponential MA are calculated for
    number of pickups and added as new features

 

Regression models used are

1.  Linear Regression

2.  Random Forest Regression

3.  XGBoost regression

 

Performance metric used is Mean Absolute Percentage Error

 
