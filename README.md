# Citi_Bike_Tableau
Module 15 Challenge for NYC Citi Bike ride share data. 

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/michael.cicchino/viz/CitiBike_Challenge_16747907410450/CitiBikeStory?publish=yes)

## Purpose 

The purpose of this analysis is to vizualize Citi Bike data for NYC using Tableau. Using Tableau allows you to easily construct stylized charts and graphs from a dataset. However, it is mainly a visualization tool. So we first clean the data in python using pandas dataframes. 

## Data Preparation

First using jupyter notebook, python, and pandas. We cleaned the dataset and convert the tripduration variable to a DateTime data type. 

## Analysis  

# 1. Checkout Times for Users 

The image below provides a chart showing the duration of the trip within the first 3 hours. 
As we can see most people get tired of peddling a bike after about 30 minutes and then there is a steep drop off. 

![dev_1](images/1_Checkout_Times.png "Dev 1 Image")

# 2. Checkout Times for Users by Gender

The image below provides a chart showing the duration of the trip within the first 3 hours broken out by Gender. It appears Males consist of more rides but follow a similar trend to Female riders.
![dev_2](images/2_Checkout_Gender.png "Dev 2 Image")

# 3. Trips by Weekday per Hour

The image below displays a heatmap of trips per Weekday by the Hour. There is clearly a trend of people taking bikes before and after normal work hours. In the morning from 7:00 AM - 9:00 AM and the evening 5:00 PM - 6:00 PM for the weekdays. 
![dev_3](images/3_Weekday_Hour.png "Dev 3 Image")

# 4. Trips by Weekday per Hour by Gender

The image below displays a heatmap of trips per Weekday by the Hour by Gender. Similar to the trend above regarding work hours. However, we can also see this trend is more profound in the Male gender.

![dev_4](images/4_Weekday_Gender.png "Dev 4 Image")

# 5. User Trips by Weekday per Hour by Gender

The image below displays a map of different User types for trips per Weekday by Gender. The map shows the breakout of Customer types. Once again the amount of Male Subscribers seems to be the outlier and a significant amount of trips. 

![dev_5](images/5_Gender_by_Weekday.png "Dev 5 Image")

# 6. Top Starting Locations Map

The image below displays a map of of the top starting locations in NYC. The map shows the most popular starting locations, and probably the most difficult to find a bike. 

![dev_6](images/6_Top_Starting.png "Dev 6 Image")

# 7. Ride per Hour of Day ( Peak Ride Hours in August)

The image below displays a map of the amount of rides by each hour. Providing insight of when the bikes are most used. The hours of 5:00 PM - 7:00 PM appear to be the busiest hours. 
![dev_7](images/7_August_Peak.png "Dev 7 Image")


## Summary

It's not a suprise of why Tableau has become popular within many industries. It is a great resource for visualizing and telling the story of data after the raw data has been cleaned. 

I would make two recommendations for analysis. 
  1. We should compare the dataset to another month to see the seasonality of the ridesharing data. In addition pulling in Weather data could be useful to see it's impact on ride volume. 
  2. We should created another data variable to measure the distance traveled using the Start Station (Latitude and Longitude) and End Station (Latitude and Longitude).  We could then filter the longest rides taken and displayed where the longest city bike trips are on a map. Also we could validate the trip duration with the trip distance variable and calculate rides average speed (by Gender, Customer Type, etc.) 



