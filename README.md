# Pyber_Analysis

## Objective
The purpose behind this analysis is to dive into the key metrics for Pyber, a ride-sharing application. This analysis explores what type of city has the most rides and how each city type compares against the total fares, both the cost of rides and what the driver earns. The ride-sharing dataset is resampled to the first quarter of 2019 in order to visualize trends between the different city types and cost of rides in USD.

To prepare this analysis the datasets providing city and ride information were first merged on a common column, "city". This allowed a dataframe a key statistics using the function "groupby" to obtain rides, drivers, and fares by city type. The output of summary metrics below shows that there is more activity in urban zones, hence more drivers and competition for customers. Drivers get paid considerably less than those operating in rural zones, where the activity is lower but wages increase due to less competition. Regardless of the higher pay for drivers in rural areas, chances are they can make more money in a shorter amount of time working in urban areas. 

![alt text](https://github.com/elenaguilarv/PyBer_Analysis/blob/master/Summarydf.PNG)

Overall, operating in urban zones is better for customers, drivers, and Pyber. Urban areas show a significantly larger number of available drivers and this can accommodate the larger population. 

![alt text](https://github.com/elenaguilarv/PyBer_Analysis/blob/master/Challenge_fares_summary.png)

## Challenges


## Recommendations
A dataset showing the average amount of rides a driver gives and what is earned by city type would provide this analysis more room for discussing the.

Based on the data from the different city types, what recommendations would you give the CEO for addressing any disparities among the city types?
Provide two additional analyses you could do to gain more insight into the data, like using other datasets.
What technical steps would you take to perform the additional analyses?
