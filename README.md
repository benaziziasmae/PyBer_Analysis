# PyBer_Analysis
Analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.

## Resources
- Data sources: [City_Data.csv](Resources/city_data.csv), [Ride_Data.csv](Resources/ride_data.csv) 
- Software : Python 3.7, Anaconda, Jupyter Notebook

## Overview of the project 

The objective of this assignment is to produce an analysis and visualization to help PyBer improve access to ride-sharing services for all city types, by creating a multiple-line graph that shows the total weekly fares for each city type, whether that be Urban, Suburban, or Rural cities. The analysis and visulaization will also help PyBer determine affordability for underserved neighborhoods.

Previously, we analyzed the ride count, average fare per ride, and average number of drivers, all categorized by the type of city. Additionally, we compared each city's metrics and the average ride fare to the total number of rides per city. 

For this challenge, we took it a step further and created a summary data frame that organized total rides, total drivers, total fares, average fare per ride, and average fare per driver and the multiple line plot.

First, we pulled our data by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

## Results
1- Total Ride by city type

The PyBer Summary DataFrame provides an overview comparison of PyBer's ridesharing services in three types of cities: **rural, surburban, and urban cities**. The summary demonstrates that there is a larger demand for PyBer among riders in urban cities compared to suburban and rural cities. 
Between January 2019 and May 2019, there were:
- 1,625 rides in urban cities, 
- 625 rides in suburban cities,
- 125 rides in rural cities. 

The figure below highlights how rides in Urban cities contributed the most to PyBer's overall rides during this five-month period.

FIG 3 TOTAL RIDES BY CITY TYPE

2- Total drivers by city type

On a similar pattern, there was also a larger volume of drivers in urban cities compared to suburban and rural cities:
- There were 2,405 drivers in urban cities, 
- 490 drivers in suburban cities, 
- 78 drivers in rural cities. 

Again, the figure below depicts the significance of drivers in urban cities during this time period.

 FIG 4 TOTAL DRIVERS BY CITY TYPE
 
 3- Total fare by city type
 
Given that there is a greater usage of PyBer in urban cities, the total fares are consequently also higher than suburban and rural cities. 
- PyBer transactions in urban cities totaled nearly $40,000 
- suburban cities totaled at least $19,000
- rural $4,000. 

The figure below demonstrates where the majority of PyBer's revenue occurred during this time period: urban cities.

![FIG 5 TOTAL FARES BY CITY TYPE](analysis/Fig5.png)

4- Average fare by ride

- In terms of costs, it appears that riders in rural cities pay on average almost $10 more for PyBer than riders in urban cities. The average fare per ride is $34.62 in rural cities whereas the average fare per ride is $24.52 in urban cities.

- Suburban cities average fare per ride falls just about $31. While it may not be good news for riders in rural cities, it is a better market for drivers in this type of city. 

5- Average fare by driver

- The average fare per driver is about $55 in rural cities, whereas the average fare per driver is about $17 in urban cities. Suburban cities' average fare per driver is about $40.

The image below show the summary of the PyBer

![Pyber_Summary](analysis/summary.PNG)














From the summary data frame, we can see that there is a trend between how populated a city is and the total number of rides, which directly affects the total number of drivers, total fare, and both averages. Although the total number of rides, drivers and fares decrease as the cities become farther from urbanized areas, the average fare per ride and per driver seems to increase. This can be explained by the accessibility of PyBer rides and drivers in rural areas. Less drivers in rural areas will may lead to a higher average fare per ride and driver, as prices increase when supply is low.

Rural cities has the least amount of drivers, rides and total fares.
Urban cities have the most amount of drivers, rides and total fares.
Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.


• The total fares in urban cities for the month of January is about 8.5 and 2.3 times the rural and suburban cities fare amount, respectively. • The total fares in urban cities for the month of February is about 6 and 2 times the rural and suburban cities fare amount, respectively. • The total fares in urban cities for the month of March is about 11 and 3 times the rural and suburban cities fare amount, respectively. • The total fares in urban cities for the month of April is about 5 and 2.5 times the rural and suburban cities fare amount respectively.


According to the plot, urban cities have the highest fares and all cities have a high peak just before the month of March. Sururban cities have lower fares compared to urban cities but higher fares compared to rural cities which have the lowest fares.

Rural Pyber users on average should expect to pay more for rides. Cities by nature have higher populations, leading to a bigger driver pool and allowing Pyber users to get lower fares.
