# 🚴‍♂️ Final Project: Statistical Modelling with Python 📊

## Project Goal 🎯

The primary goal of this project was to explore the interplay between city bike-sharing services and the surrounding Points of Interest (POIs) using various data sources, including CityBikes, Foursquare, and Yelp APIs. Through data collection, analysis, visualization, and modeling, we aimed to understand how the availability of bikes at different locations correlates with the characteristics of nearby POIs. This analysis will provide insights into urban mobility and inform smarter city planning and improved services.

## Process 🔄

### Part 1: Connecting to CityBikes API 🚲

**Task Overview**:
- Engaged with the CityBikes API to understand bike-sharing data.
- Explored the API structure and data.
- Selected Strasbourg as the CityBikes location and retrieved data on all available bike stations.
- Obtained latitude, longitude, and bike availability for each station.
- Parsed the data into a Pandas DataFrame.

### Part 2: Connecting to Foursquare and Yelp APIs 🌟🍽️

**Task Overview**:
- Utilized Foursquare and Yelp APIs to gather POI data around bike stations.
- Focused on POIs such as Parks, Pubs/Bars, Cafes, and Landmarks.
- Established connections to both APIs.
- Created DataFrames for Yelp and Foursquare data.
- Analyzed and compared the quality and coverage of data from both APIs.

![bike availability](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/514f69f6-8da6-4dcd-9e9e-3c1603b11b26)

![bike](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/451355d7-9c9b-48c2-bb18-8e090f45202f)


### Part 3: Joining Data 🔗

**Task Overview**:
- Merged data from CityBikes with POI information from Yelp.
- Used different data visualization techniques to explore the merged data.
- Created an SQLite database for Yelp, Foursquare, and CityBike data to store the collected information, considering the database structure.


![bike](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/e6a2b76d-5de3-46b0-a765-efc2572d91d7)


### Part 4: Building a Model 🏗️

**Task Overview**:
- Developed a regression model to analyze the relationship between bike availability and POI characteristics.
- Used the 'statsmodels' module to build the regression model.
- Interpreted the model results and derived insights.

### Part 5: Cross-validation, PCA, and Hyperparameter Optimization 🔍

**Task Overview**:
- Performed cross-validation, applied PCA for dimensionality reduction, and conducted hyperparameter optimization to ensure the model was not overfitting and to find the best parameters for optimal performance.

## Results 📈

- **Significant Findings**:
  - Parks have a significant effect on the model based on their p-value.
  - The R and R-squared values were very low, indicating that POIs didn't have much effect on bike availability in general.

 <img width="1109" alt="Screenshot 2024-06-18 at 12 14 09 PM" src="https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/4bcdbc7b-5ec5-462e-b925-927c3328557d">

  

## Challenges ⚠️

- Retrieving accurate information about POIs directly after using the API.

## Future Goals 🚀

- Understand the data better and explore different models to improve the R and R-squared values.
