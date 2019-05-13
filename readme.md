# Will this happen to you? Predicting flight delays
Larry Finer  
February 2019

The goal of this project was to look at U.S. flight data to determine the factors that lead to flight delays. The target audience is a traveler who is planning a trip and could use this information before booking to assess the likelihood that a particular flight will be delayed. I used the [2015 U.S. flights dataset on Kaggle](https://www.kaggle.com/usdot/flight-delays). This dataset contains a main data table with nearly 6 million flights, as well as auxiliary tables with data on airports and airlines. I created a 0/1 variable indicating whether a flight was delayed by defining a delay as 15 minutes or more between scheduled and actual arrival. Key predictive features I considered were month of the year, day of the week, time of day, length of flight in miles or time, airline, departure airport, and arrival airport. I also merged in and looked at 2015 weather data from the [National Oceanic and Atmospheric Administration](https://www.ncdc.noaa.gov/) — specifically, the FTP site ftp://ftp.ncdc.noaa.gov/pub/data/noaa/2015/ — as another predictive feature.


The [Jupyter Notebook file](Predicting%20flight%20delays.ipynb) above contains the code to carry out these steps.

A presentation summarizing the results of the project is also contained in this repository and in two Tableau visualizations.

- [Presentation summarizing the results of the project in Keynote format](Predicting%20flight%20delays.key)
- [Presentation in PDF](Predicting%20flight%20delays.pdf)
- [Tableau heatmap of delays by day of week and time of day](https://public.tableau.com/profile/tableau.user1856#!/vizhome/Heatmap_72/Heatmap)
- [Tableau map of delays by origin airport](https://public.tableau.com/profile/tableau.user1856#!/vizhome/Originmap/Delaysbyoriginairport)
