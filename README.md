# PyBer_Analysis

## Overview of PyBer Analysis
The purpose of this project is to provide an analysis on the relationship between types of cities and the number of drivers/riders, total fares by driver and the total number of rides that occured between January 2019 until April 2019. The results will be presented using several types of visual aids in order to quickly summarize the findings for the CEO to review.

## Purpose
The purpose of this project was to perform an exploratory analysis on the data inside the CSV files which will be aided by some visualizations. These visualizations (Scatter Plots and Pie Charts) will be performed by utilizing the functionality of Python scripting. Python libraries such as Pandas and Matplotlib inside our Jupyter Notebook will help us in accomplishing this task. This will help us showcase the relationship between the type of city, the number of drivers/riders as well as the percentage of total fares, riders by type of city as per the request of PyBer's CEO to improve PyBers access to ride-sharing service and determine affordability for certain neighbourhoods.

## Files Used:
[city_data.csv](Resources/city_data.csv)

[ride_data.csv](Resources/ride_data.csv)

## Results:
Here are the computed results of our analysis. As we can see from the below snippet: 
1. The number of rides are abundantly more in Urban areas as opposed to Suburban and Rural areas. 
2. Another key pint is that the `Average Fare per Ride` is increasing due to the lack or less use of ride-sharing services as we move from Urban to Suburban and finally to Rural areas.
3. Finally, we can interpret that the `Average Fare per Driver` is also increasing as we move from Urban to Suburban and finally to Rural areas.
<p align="center"><img src="https://github.com/mubeenkh4u/RBC-Module-5-Pyber-Analysis/blob/main/analysis/Pyber_Summary_Clean.png"></p>

The chart below shows us:
1. As the distance increase in the rides, the average fare increases as well. 
2. Urban cities typically have higher amounts of Total Fares, this is attributed to the excessive use of the service as opposed to Suburban and Rural areas.
3. The higher `Average Fare per Driver` in rural areas depicts the lack of drivers and ride-sharing service in these areas.
<p align="center"><img src="https://github.com/mubeenkh4u/RBC-Module-5-Pyber-Analysis/blob/main/analysis/PyBer_Fare_Summary.png"></p>

## Summary:
From the above analysis we can conclude that the `Average Fare per Rides` increases as we move from Urban to Suburban and finally to Rural areas:
1. This is credited to the lack of drivers in the areas
2. Less accessibility to the service increasingly as we move from Urban to Rural areas.
3. The bulk of the business and profit is from Urban aras.

## Recommendations:
We can improve the accessibility of the service and its quality by the following:
1. Provide incentives to drivers to increase their hiring rate in Suburban and Rural areas.
2. Provide discounts to riders for using the service in Suburban and Rural areas.
3. Lower the intial cost of the fare to further promote accessibility to the ride-sharing service.
