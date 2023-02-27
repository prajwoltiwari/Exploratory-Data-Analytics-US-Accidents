# Exploratory-Data-Analytics-US-Accidents

Data Preprocessing and Cleaning:

- Loaded the file using Pandas
- Looked at the information present in the file, the columns, types
- Identified incorrect or missing values


Question ideas to explore in the dataset:

- Are there more accidents in warmer or colder areas?
- Which 5 states have the highest number of accidents? How about per capita?
- Does New York show up in the data? It is the most populous city in the USA and it does not show up in the top 20 accidents cities.
- Among the top 100 cities in the number of accidents, which states do they occur in most frequently?
- What time of the day do accidents occur most frequently?
- Which day of the week occurs more accidents?
- Which months have more accidents?
- What is the trends of accidents over years (decreasing or increasing?


Exploratory Analysis and Visualization:

Columns that were analyzed:

- City: Barh plot, histplot, distplot were used to analyze accidents by cities and the distribution of the accidents by cities
- Start time: Analysis was done for hour of day, days in week, weeks in months and months in year to see the distribution of accidents according to these datetime frames.
- Start lat, Start lng: Scatterplot was made to see the distribution of accidents as per the latitude and longiture. Folium HeatMap was use to create a heat map in the map of US in a sample size of 1% of the dataframe.


Summary and Conclusion:

- No data for New York
- Analysis done in dataset containing 2.8 million records
- The number of accidents per city decreases exponentially
- The accidents are lower on weekends and are almost evenly distributed in the weekdays
- The distribution of number accidents by hour is different on weekends as compared to the weekdays.
- On Sundays, the peak occurs between 10am and 8pm, unlike weekdays
- Need to dig deeper into the number of accidents per month. Seems like there are more accidents in the end of the year when the winter is there. More specifically, highest why in the december?
- Much data might be missing in different years due to which the distribution shows more accidents in Deceber.
- We also might have different sources of data. It might be important to compare the data from different sources.
- Less than 5% of the cities have more than 1000 yearly accidents
- Over 1200 cities have reported only 1 annual accident.
- The Folium HeatMap shows higher temperature in the costal regions, both east and west coast and low temperature in the central area of the USA
