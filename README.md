# Bike-Rental-Demand-Analysis

**Overview**

This project aims to predict daily bike rental demand using machine learning. The dataset includes weather conditions, seasonal information, and calendar-related features such as temperature, humidity, windspeed, working days, and holidays.
After cleaning and preparing the data, relevant features were selected and scaled to improve model performance. A Linear Regression model was then trained to understand how these factors influence the total rental count (cnt). The model was evaluated to measure its predictive accuracy.
Overall, the project demonstrates how data preprocessing, exploratory analysis, and regression techniques can be applied to solve a real-world prediction problem.


**Data Set Information**

This dataset is referred from Kaggle & UCI Repository.
Kaggle source: https://www.kaggle.com/datasets/yasserh/bike-sharing-dataset

**Data Description**

Attribute Information:

- instant	: Row index 
- dteday : Date 
- season	: 1=Spring, 2=Summer, 3=Fall, 4=Winter
- yr	: 0=2018, 1=2019
- mnth	: Month (1–12)
- holiday	: 1 if holiday
- weekday	: Day of week (0=Sun)
- workingday	: 1 if working day
- weathersit	: 1=Clear, 2=Mist, 3=Light rain, 4=Heavy rain
- temp	: Normalized temperature
- atemp	: Normalized feels-like temp
- hum	: Normalized humidity
- windspeed	: Normalized wind speed
- casual	: Rentals by non-registered users
- registered	: Rentals by registered users
- cnt	: Total rentals
