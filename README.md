# PyBer_Analysis

## Overview of PyBer Analysis
In order to help PyBer, a Python based ride-sharing app company, improve access to ride-sharing servive and determine affordability for underserved neighborhoods, we use the Jupyter Notebook and Pandas to inspect csv large dataset files, merge data sets, perform mathematical calculations and create data frame. After processing exploratory analysis on the data, we create different types of visualization(e.g. pie, scatter, bar, line plot) by using the python's plotting library Matplotlib. The quality figures plots tells visual story about the data that showcase the relationship betwen the number of drivers and riders as well as the type of city.

## Result of PyBer Analysis
From the PyBer Analysis, we provide a multiple line graph that shows the total weekly fare for each city type and a ride-sharing summary DataFrame group by city type.

first of all, in the ride-sharing summary DataFrame we can see that the total number of rides, drivers and fares are increasing as the scale of the city increase. But the average fare per Ride and per driver are decreaseing as the scale of the city increase. 

![ride_sharing_summary_df](https://github.com/hayden0098/PyBer_Analysis/blob/main/analysis/ride_sharing_summary_df.jpg)

secondly, the multiple line graph shows total fare of urban every week is having the most total fare compare to type Rural and Suburban of city, the Rural city is having the lowest totla fare. 

![PyBer_fare_summary](https://github.com/hayden0098/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Overall, rural city's total fare was fluctuant in the first two months but tended to be stable after February. Its total fare reached the peak at $500 in April. The total fare of suburban had a slight wave between January and February. The peak at around $1,500 was been reached near the end of February. Despite the initiaL fluctuation, the total fare of suburban city stayed stable in March and it shows an upward trend thereafter. For Urban city, the total fare of ride-sharing rose steadily from January to February and reached the maximum of $2,500 at the end of February and the beginning of March. It fluctuated dramatically in March but became gradual falls in April.

## Summary
Three business recommendation for addressing disparities among city types based on the results from analysis:

   1. ###### Increase number of drivers:
    In consideration of demand in Rural city, the main emphasis should be on increasing the number of drivers 
    in both Rural and Suburban city to make the total drivers from these two types of city have at least 1/4 % shares 
    of total drivers by the all city type. Among them, the rise of number of drivers in Suburban should be more than Rural.
    With the rise of supply (the number of drivers), the access of the ride-sharing can be improved.
    
![total_driver_by_cityType](https://github.com/hayden0098/PyBer_Analysis/blob/main/analysis/%25_total_driver_by_cityType.png)

   2. ###### Adjust fare per ride:
    Decrease the fare per ride to an affordable range for neiborhood in Rural city in order to stimulate the 
    number of rides in Rural city.

   3. ###### Promotion event:
    According to the mutiple line graph, after March, the total fare in Urban city became fluctuated, and fell in April. 
    It is suggested that some promotion event be provided in order to retain existing customers and attract potential customers 
    which could make the total fare line become stable and prevent the falls after March.
