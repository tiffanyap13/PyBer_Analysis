# PyBer_Analysis
## Overview
My new boss at PyBer has given me a brand-new assignment. I have been asked to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I will create a multiple-line graph that shows the total weekly fares for each city type. I will ultimately summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.
## Data
### Background
 - After downloading and merging two data files (city data and ride data), the following analysis was completed to attain this summary chart for the Urban, Suburban, and Rural city types: ![summary](Resources/Summary.png)
   - Number of rides by city type
   - Total ride count by city type
   - Total drivers by city type
   - Total fare by city type
   - Average fare per ride per city type
   - Average fare per driver per city type

## Results
The next step was to filter the data to look at 01-01-2019 through 04-29-2019 and resample the data by week. The following graph was created as a result. 
![Total Fare by City Type](analysis/PyBer_fare_summary.png)

### Analysis
#### Summary 
The difference in ride-sharing data among the different city types is drastic.  Rural areas have less requested rides (125) and less drivers (78) compared to Suburban and Urban areas. The Urban areas have the largest number of requested rides (1,625) and also drivers (2,405).  However, the most expensive Average Fare per Ride and Average Fare per Driver are seen in the Rural area at $34.62 and $55.49, respectively.  In turn, the Urban areas experience the least expensive Average Fare per Ride and Average Fare per Driver, at $24.53 and $16.57, respectively.  The Suburban results fall in the middle at 625 rides, 490 drivers, $30.97 Average Fare per Ride, and $39.50 Average Fare per driver.
#### Total Fare by City Type
When looking at the graph, it is easy to see that the Urban Fares are highest, which is expected based upon the volume seen in the summary.  Likewise, the Rural areas experience less fares on average per week than both Urban and Suburban areas.


## Recommendation
Based on the results, I have three business receommendations for the CEO for addressing any disparities among the city types.


