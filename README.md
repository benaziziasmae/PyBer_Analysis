# PyBer_Analysis
Analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.

## Resources
- Data sources:
- Software : Python 3.7.1, Anaconda, Jupyter Notebook

## Overview of the project 

The objective of this assignment is to produce an analysis and visualization to help PyBer improve access to ride-sharing services for all city types, by creating a multiple-line graph that shows the total weekly fares for each city type, whether that be Urban, Suburban, or Rural cities. The analysis and visulaization will also help PyBer determine affordability for underserved neighborhoods.

Previously, we analyzed the ride count, average fare per ride, and average number of drivers, all categorized by the type of city. Additionally, we compared each city's metrics and the average ride fare to the total number of rides per city. 

For this challenge, we took it a step further and created a summary data frame that organized total rides, total drivers, total fares, average fare per ride, and average fare per driver and the multiple line plot.

First, we pulled our data by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

