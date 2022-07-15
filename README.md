# PyBer_Analysis
## Project Overview
The goal of this project was to take rideshare data and display the rates being charged for a ride on a per week basis, while accounting for three area types, urban, suburban, and rural. The information is tracked by area type to display the differences in fare over time.

## Resources
- Data Source: city_data.csv , ride_data.csv
- Software: Python 3.7.6, Jupyter Notebook

## Results
The analysis of the ridesharing data shows that:
- From most expensive to least expensive the city types rank as such: Urban, Suburban, Rural
  - This does not change over the entire extent of the time measured, 1/1/19 - 4/29/19

- ![PyBer_fare_summary](https://user-images.githubusercontent.com/107013312/179120922-03f8a9a2-2174-4512-a12d-365432720e3c.png)

- Shown below are the total rides, total drivers, total fares, average fare per ride, average fare per driver, and total fare, all broken down by city type
- ![pyber_summar_df](https://user-images.githubusercontent.com/107013312/179120880-b6e4c24d-018c-4188-aedd-8b2a2511d79d.png)

- Urban areas have the most total rides, total drivers, and total fares, but have the lowest average fare per ride and lowest average fare per driver
- Suburban areas are in the middle in every category but skew closer to rural areas than urban
- Rural areas have the fewest total rides, total drivers, and total fares, but have the highest average fare per ride and highest average fare per driver.

## Summary
Based on the results, a few business suggestions could be made addressing the disparities among the city types. First, the reason for total rides being so much lower in suburban and rural areas could be attributed to the higher average fare prices. Dropping the fare price in those areas could increase the number of rides and hopefully revenue as a whole. Second, there are many more drivers than rides given in urban areas, while there are fewer drivers than rides in rural and suburban. It would seem prudent to encourage drivers in the urban areas to accept rides in the other two area types in order to level out the disparity in the drivers per ride ratio. Third, the fare per driver seems to have an inverse relationship with the number of drivers in the area. If the area with the drivers are making the least also has the most people willing to drive, this would suggest that drivers in the other areas could be paid less and would likely have no impact on the number of drivers in the area. 
