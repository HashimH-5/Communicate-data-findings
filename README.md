# Ford GoBike System Data
## by Hashim Hashim


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 183,412 and 16 different features on information about the bicycle usage service. The dataset is hosted on Udacity servers via this link  https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

In the exploration, I found out that the Distribution of trips in seconds took on a large range of values, so I used the a log transform on the x-axis and  changed the variable into minutes. Under the transformation, the distribution became a normal distribution with the average trip duration at below 25000 minutes.

Subscribers have shown to take the most number of trips during the weekdays while cutomers took more trips towards the weekends. Also, most of the subscribers use bicycle service at 0800 in the morning and at 1700hrs in the evening for the subscribers, While Customers used the service mostly at noon and took longer durations than subscribers due to their flexible time.

Outside the main variable of interest, there is a relationship between the number of males who rent the bikes and the duration of the trips. Male gender is observed to take longer trip duration than females who rent bikes.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the duration, user type and days of the week to find most of the insights. I start by introducing the
duration in seconds variable, followed by the pattern in type of users distribution, then plot the distribution of trips during the week.