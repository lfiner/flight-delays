# Will this happen to you? Predicting flight delays
Larry Finer  
February 2019

The goal of this project was to predict the probability that a flight would be delayed, using characteristics of the artwork and artist. The project entailed scraping and downloading artist and artwork data, cleaning the data, and then developing a linear regression model through feature engineering, adding polynomial features, and testing regularization approaches.

look at U.S. flight data to determine the factors that lead to flight delays. The target audience is a traveler who is planning a trip and could use this information before booking to assess the likelihood that a particular flight will be delayed. I will use the 2015 U.S. flights dataset on Kaggle (https://www.kaggle.com/usdot/flight-delays). This dataset contains a main data table with nearly 6 million flights, as well as auxiliary tables with data on airports and airlines. I will create a 0/1 variable indicating whether a flight was delayed by defining a delay as a certain number of minutes (perhaps 15) between scheduled and actual departure or scheduled and actual arrival. Key predictive features I will consider are month of the year, day of the week, time of day, length of flight in miles or time, airline, departure airport, and arrival airport. I could also look at specific aircraft (the dataset contains tail numbers for the 5,000 planes in the dataset). If possible, I will also merge in and look at daily or hourly weather as another predictive feature.


The [Jupyter Notebook file](Predicting%20flight%20delays.ipynb) above contains the code to carry out these steps.

A presentation summarizing the results of the project is also contained in this repository and in two Tableau visualizations.

- [Presentation summarizing the results of the project in Keynote format](Predicting%20flight%20delays.key)
- [Presentation in PDF](Predicting%20flight%20delays.pdf)
- Tableau heatmap of delays by day of week and time of day
- Tableau map of delays by airport
