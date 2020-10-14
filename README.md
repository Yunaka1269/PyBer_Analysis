# PyBer_Analysis

##Create a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type

##Results:

Total rides, total drivers, and total fares are direct relationship. However, they are inverse relationship with average fare per ride and average fare per driver. For instance, rural city are has the least number of rides, total drivers, and total fares, yet records the highest average fare per ride and average fare per driver. My assumption is that there are less potential riders(population) as well as the drivers out there in rural city but each ride requires the longest distance among city types. Inversely, urban city has the highest number of riders and drivers yet the average fare is the lowest because of the short distance ride. Additionally, there are more drivers than rides in urban city so there are more competition.

[PyBer_Summary](https://github.com/Yunaka1269/PyBer_Analysis/blob/main/analysis/PyBer_Summary.PNG)

[Total_Fares_By_City_Type](https://github.com/Yunaka1269/PyBer_Analysis/blob/main/analysis/Total_Fares_By_City_Type.png)

###Resources
  - Data Source: city_data.csv, ride_data.csv
  - Software: Jupyter Notebook 6.1.4
  
##Summary:

Business recommendations that I could offer to address any discrepancies among the city types are followings;

1. analyze each ride data includes but not limited to the time of day/day of the week/ride distance (or duration)/location
2. analyze rider's rating on drivers
3. analyze rider's demographics (gender, age, number of passengers per ride, occupation) 

This way, PyBer can shift drivers, who tends to receive a higher ratings, heavily according to the demand and identify the target riders easily. 
