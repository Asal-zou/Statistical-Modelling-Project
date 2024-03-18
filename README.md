# Final-Project-Statistical-Modelling-with-Python

# Project Goal

The primary goal of this project was to explore the interplay between city bike-sharing services and the surrounding Points of Interest (POIs) using various data sources, including CityBikes, Foursquare, and Yelp APIs. Through data collection, analysis, visualization, and modelling, we aimed to understand how the availability of bikes at different locations correlates with the characteristics of nearby POIs. This analysis will provide insights into urban mobility and inform smarter city planning and improved services.

## Process

### Part 1: Connecting to CityBikes API

- **Task Overview**:
  - Engaged with the CityBikes API to understand bike-sharing data.
  - Explored the API structure and data.
  - Select Strasbourg as my CityBikes location and retrieve data on all available bike stations.
  - We obtained latitude, longitude, and bike availability for each station.
  - Parse the data into a Pandas DataFrame.

### Part 2: Connecting to Foursquare and Yelp APIs

- **Task Overview**:
  - Utilized Foursquare and Yelp APIs to gather POI data around bike stations.
  - The POI was Park, Pub/Bar, Cafe and Landmark.
  - Established connections to both APIs.
  - Created DataFrames for Yelp and Foursquare data.
  - Analyze and compare the quality and coverage of data from both APIs.

### Part 3: Joining Data

- **Task Overview**:
  - Merged data from CityBikes with POI information from Yelp.
  - Used different data visualization techniques to explore the merged data.
  - Created an SQLite database for Yelp, Foursquare and Citybike to store the collected data, considering the database structure.

### Part 4: Building a Model

- **Task Overview**:
  - Develop a regression model to analyze the relationship between bike availability and POI characteristics.
  - Use the 'statsmodels' module to build the regression model.
  - Interpret the model results and derive insights.

## Results

- The Park has a significant effect on the model based on their p-value.
- The R and R-squared were very low, showing the POIs didn't have that much effect on the bike availability in general.

## Challenges 

- Retrieving accurate information about POI directly after using API.

## Future Goals

- I like to understand the data and explore different models to get the R and R-squared.
