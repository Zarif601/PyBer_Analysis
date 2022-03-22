# PyBer Analysis

## Overview of the analysis

This project is an analysis of ride-sharing data for a company called PyBer. The analysis provides a detailed summary of the different key elements of the data by grouping it by city type: Rural, Surburban or Urban. It also contains a graph to show the total weekly fares for each city type.

# Purpose

The ride-sharing data has been analyzed to present to the PyBer company so that they can make decisions about which type of cities they need to invest in and how much to invest. Making an analysis by separating the city types into Rural, Suburban and Urban makes it easy to understand and make decisions about how each type of cities should be worked on.

## Results

A summary dataframe has been created that contains all the relevent information about each city type as shown below:

![PyBer Summary](https://github.com/Zarif601/PyBer_Analysis/blob/main/Resources/PyBer_summary.png)

From the above dataframe we can see that Urban cities reported many more rides than other types of cities. As such the total number of drivers in Urban cities is also much higher. As such, we can also see that the total fare is much higher in Urban cities. Suburban cities had the second most rides, number of drivers and total fare and Rural cities had the least. 

However, looking at the 'Average Fare per Ride' column, we can see that average fare for a ride is the cheapest in Urban cities, and Rural cities had the highest average fare per ride. The same pattern is also seen in the 'Average Fare per Driver' column, where Rural driver fares were much higher compared to Suburban and Urban cities. Urban city's fare per driver is the by far the lowest.

There seems to be a clear correlation between the total number of rides in each city and the average fares generated per ride in those cities. It looks like the higher the number of rides, the lower the average fare generated.

The analysis also contains the weekly fluctuation of average fare for each city type. The graph which shows this information is as below:

![Weekly Fare By City Type](https://github.com/Zarif601/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

The fluctuation of the average fares seem consistent for all three types of cities. We can see dips in March for all cities and overall there doesn't seem to be anything that stands out throughout the year.

## Summary

Given the results shared above, here are three business recommedations to PyBer:

1. To balance out the distribution of fares, more rides need to me made available in Rural and Suburban cities. 
2. Rural areas also require more drivers, followed by Suburban cities.
3. Urban cities can be asked to share some of their drivers and rides with their neighboring Rural and Suburban cities on a need basis to even out any fare disparities.

Following the above recommendations should hopefully even out the dare distrubution between Rural, Suburban and Urban cities.
