# **Tableau Data Analysis**  
## **NYC Citibike Trends in 2017**  
### **By: Luis Gomez**  


### Data Extraction, Treatment and Loading (ETL)  

The data used for this Tableau workbook was obtained from the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage. This website provided *.csv* files for a month's worth of data starting from 2013 until December 2020.  

For the purposes of this assignment, data corresponding to 2017 was used.  

After the data files were downloaded, R was used to process the datasets, deleting unneeded columns and standardizing the column names and formats, as files for the 3 first months of 2017 had a different column name structure than data for the rest of the year.  

After cleaning, data was ready to be loaded into Tableau.  

The workbook can be accessed using the following link: [2017 NYC Citibike Trends](https://public.tableau.com/app/profile/luis.gomez7978/viz/2017NYCCitibikeTrends/NYCCitibikeTrendsin2017)

### Tableau Visualizations  


After the data was loaded into Tableau, an exploration of the dataset was performed. Two unexpected phenomena were found and pertinent visualizations were loaded into dashboards, as well as an informative map that shows the busiest stations. All of this can be seen in the submitted story.  


#### **Citibike Trip Metrics By Gender in 2017**  


When observing the total number of trips taken in 2017 by gender, the total amount of trips taken by men triples the amount of trips taken by women. However, the average trip duration of female customers is higher than the average trip duration of male customers in 2017.  

When the average trip duration is broken down by month, the amount of minutes spent on a bike in average by a female customer was always higher than the amount of minutes spent on a bike by a male customer. The month of April was the month in which men spent the most amount of minutes on average on a bike, whereas the amount of time spent on average by women was the highest in the month of August.  

One interpretation of the data is that the female customer base might be more active than the male customer base, and could be using the bikes for non-leisure purposes (it could be for general transportation purposes or for fitness purposes). Additional data would be needed to support this hypothesis.  


#### **Top 10 Stations by Minutes Ridden**  

This map shows the top 10 stations by minutes ridden and distinct end stations of trips started in that station, denoted by size and color.  

The top station, both in total minutes ridden starting from this station and distinct final destinations, is Pershing Square North. Pershing Square North is the main Citibike station located in Central Station, which is one of the top tourist destinations in New York City. The rest of stations are located in the borough of Manhattan, which attracts people from all over the world.  

When the data is broken down by month, it can be appreciated that the top month for Pershing Square North is October, which is interesting given the fact that October is one of the months of fall. Conventional wisdom or intuition might lead us to think that the top month for this station would be April or May, months of spring in which the temperature is more suited for bike riding, but data debunks this logic.  

Another interesting piece of data is that in July, the West St & Chambers St very slightly beat Pershing Square North in total minutes ridden starting from this station.  

#### **Most Popular Stations**  

The map indicates the most popular stations using dots with two different dimensions:  

- Size indicates the amount of trips starting from this station.
- Color indicates the amount of trips ending at this station.

This map also shows zip code data overlaid on it.  

In both metrics, it can be appreciated that Pershing Square North is the biggest station by volume of starting and finishing trips.  

Overall, the map strengthens what the previous dashboard (*Top 10 Stations by Minutes Ridden*) demonstrated, which is that stations located in Manhattan attract the biggest amount of bike rentals.  

The most popular zipcodes by dot density and magnitude are: 

- 10001
- 10003
- 10018
- 10017
- 10018
