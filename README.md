# Pyber_Analysis

## Objective
The purpose behind this analysis is to dive into the key metrics for Pyber, a ride-sharing application. This analysis explores what type of city has the most rides and how each city type compares against the total fares, both the cost of rides and what the driver earns. The ride-sharing dataset is filtered to the first quarter of 2019 in order to visualize clear trends between the different city types and cost of rides in USD.

To prepare, the datasets providing city and ride information were first merged on a common column. This allowed for the key numbers to be summarized in a dataframe using the function "groupby" to obtain rides, drivers, and fares specifically by city type. The output of summary metrics below shows that there is more activity in urban zones, hence more drivers and competition for customers. Urban drivers make less than those operating in rural zones, where the activity is lower but wages increase due to less competition. Regardless of the higher pay for drivers in rural areas, it could be argued that they make more money in a shorter amount of time and with less gas mileage working in urban areas. This would be a good point for further analysis.

![alt text](https://github.com/elenaguilarv/PyBer_Analysis/blob/master/Summarydf.PNG)

Overall, operating in urban zones is better for customers in need of getting around, drivers looking for quick work, and Pyber's business. Urban areas show a significantly larger number of available drivers and this also accommodates the larger populations.

![alt text](https://github.com/elenaguilarv/PyBer_Analysis/blob/master/Challenge_fares_summary.png)

## Challenges
Preparing the dataset for a line plot needed a few tricks. It was important to be mindful of the structure of the pivot table. In order to create the line plot, the original dataframe had to take on a different presentation. The date had to become the index, city types were converted to the columns and the fares were changed to the values. When the fares between January and April of 2019 were located, some showed "NaN", but once it was resampled to "W" meaning weekly fares, all of the values returned.

## Recommendations
As referenced above, data on the average amount of rides a driver completes in day, where, and what they earn on average would provide this analysis more room for discussion. In general urban areas give Pyber more value. Redesigning this analysis to different times of the year-- during holidays, back-to-school season, or festivals, could show new insights. These events have a big impact on ride-share activity and they do not always occur in urban areas. Obtainining information on festivals and city events throughout the year, such as dates and total attendees, could help Pyber scale up their driver pool prior to them happening. 
