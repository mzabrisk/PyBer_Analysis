# PyBer Analysis

## Overview
After our initial analysis of the PyBer data, we were asked to provide some additional information:

1. A DataFrame sorted by city type, showing Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Far per Driver.

2. A graph showing total fares by city type over time. 

With the graph, our CEO wanted to see if there was any discernable pattern over time that wasn't obvious when looking at the agreggated data from our initial analysis. The DataFrame provides an easy way to look at the Total Ride, Total Driver, and Total Fares data, as well as a new metric in Average Fare per Driver. The data for Median Fare per Ride was present in the previously created box and whisker plots, but she wanted the mean as well as all the data in one table.

## Results

In general, when looking at the PyBer summary DataFrame, the summed or counted data (Total Rides, Total Drivers, and Total Fares) are greatest in Urban Areas, and least in Rural areas, with Suburban areas falling in between. The averaged data (Average Fare per Ride and Average Fare per Driver) are greatest in the Rural areas and smallest in Urban areas, with Suburban areas falling in between. The complete summary DataFrame can be seen here:

![](https://github.com/mzabrisk/PyBer_Analysis/blob/447ea74b7c3fd0d5f9f6dd0b5a2c90adfac929a8/analysis/PyBer_summary_df.png)

Examining the below line graph, which shows total fare by city type, on a week to week basis, all three city types follow a relatively consistent pattern. During all weeks in the examined time frame (January 2019 through April 2019), Urban areas have the highest total fare, followed by Suburban areas, with Rural areas having the lowest total fare.

![](https://github.com/mzabrisk/PyBer_Analysis/blob/447ea74b7c3fd0d5f9f6dd0b5a2c90adfac929a8/analysis/PyBer_fare_summary.png)

## Summary

In short, further analysis is needed in order to make any major conclusions from the data. Conclusions, as well as recommended further analysis are as follows:

1. The number of drivers in Urban areas exceeds the ride demand. This leads to a low value for average fare/driver. A couple of potential solutions:
    - A market analysis needs to be conducted to determine if there is potential for more demand. If there is, more money needs to be spent on advertising in Urban areas to increase the number of riders to match the ride supply (drivers). If the market seems to be completely tapped, it may be time to reduce the number of drivers in the Urban areas, thus increasing the average fare/driver, and keeping the drivers happier.

2. On the surface it appears that there might be more potential in the Rural market since the total fares is significantly less than either Urban or Suburban.
    - A market analysis needs to be conducted to determine whether there is potential for greater demand in the rural areas. If there is, it also needs to be determined whether or not there is potential for more supply (either more drivers, or more rides given by each current driver). If there is potential for both, efforts should be made to increase both. 

3. An analysis should be conducted taking into account the population of the various cities and city types. It's completely possible that the difference in rides given is purely a factor of population, and not related lower utilization rates. 