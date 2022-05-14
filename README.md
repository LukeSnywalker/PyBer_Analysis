# PyBer Analysis

## Overview

The purpose of the new analysis was to summarize the differences in ride sharing data between each city type, and to determine and compare the total weekly PyBer fares for each city type using Pandas DataFrames and line plots.

## Results

![Ride sharing summary](/analysis/Ride_Share_Summary.png)

Urban cities have the most rides, taking up more than 68.4% of the total ride count with 1625 rides.  

![Ride count per city type](/analysis/Fig2.png)

![Percentage of total rides per city type](/analysis/Fig6.png)

They also have the most drivers of the three city types, taking up an even higher percentage of the total: 80.9% with 2405 drivers. There is one outlier in the number of rides for urban cities though, and there seems to be a high degree of error for both these data points, meaning the data could have counted incorrectly. Rural cities take up a very small percentage of both total rides and total drivers, with 5.3% and 2.6% respectively.

![Driver count per city type](/analysis/Fig4.png)

![Percentage of total drivers per city type](/analysis/Fig7.png)

Total fares trend the same way as the ride and driver counts, with urban cities having the highest total, then suburban, then rural.

![Percentage of total fares per city type](/analysis/Fig5.png)

The average fare per ride and per driver have inverse relationships with the total rides and drivers per city, with rural cities having the highest fares and urban cities having the lowest.

![Average ride fare per city type](/analysis/Fig3.png)

The graph below displays this relationship in more detail, with each bubble representing an individual city and the size of each bubble representing its driver count.

![Summary bubble graph](/analysis/Fig1.png)

This line chart displays the changes in total fare for each city type from January 1st to April 28th. There does not seem to be a significant upwards or downwards trend in this time period, but there is a slight peak for each city type in late February, with suburban cities having the highest peak.

![Line chart of total fares per city type for January through April](/analysis/Pyber_Fare_Summary.png)

## Summary

Three recommendations I have to address the disparities among the cities are employing more drivers in rural and suburban cities, increasing urban fares and decreasing rural fares to encourage more ride-sharing in rural cities, and possibly decreasing fares for both urban and suburban cities in late February.