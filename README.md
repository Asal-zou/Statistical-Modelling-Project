 🚴‍♂️ Final Project: Statistical Modelling with Python 📊

## Project Goal 🎯

The primary goal of this project was to explore the interplay between city bike-sharing services and the surrounding Points of Interest (POIs) using various data sources, including CityBikes, Foursquare, and Yelp APIs. Through data collection, analysis, visualization, and modeling, we aimed to understand how the availability of bikes at different locations correlates with the characteristics of nearby POIs. This analysis will provide insights into urban mobility and inform smarter city planning and improved services.

## Process 🔄

### Part 1: Connecting to CityBikes API 🚲

**Task Overview**:
- Engaged with the CityBikes API to understand bike-sharing data.
- Explored the API structure and data.
- Selected Strasbourg as my CityBikes location and retrieved data on all available bike stations.
- Obtained latitude, longitude, and bike availability for each station.
- Parsed the data into a Pandas DataFrame.
- **Challenges**: Understanding the API structure and ensuring the data retrieved was accurate and complete.

### Part 2: Connecting to Foursquare and Yelp APIs 🌟🍽️

**Task Overview**:
- Utilized Foursquare and Yelp APIs to gather POI data around bike stations.
- Focused on POIs such as Parks, Pubs/Bars, Cafes, and Landmarks.
- Established connections to both APIs.
- Created DataFrames for Yelp and Foursquare data.
- Analyzed and compared the quality and coverage of data from both APIs.
- **Challenges**: Handling API rate limits and ensuring data consistency across different sources.

### Part 3: Joining Data 🔗

**Task Overview**:
- Merged data from CityBikes with POI information from Yelp and Foursquare.
- Used different data visualization techniques (e.g., scatter plots, heatmaps) to explore the merged data.
- Created an SQLite database for Yelp, Foursquare, and CityBike to store the collected data, considering the database structure.
- **Challenges**: Ensuring data integrity and dealing with discrepancies between different datasets.

### Part 4: Building a Model 🏗️

**Task Overview**:
- Developed a regression model to analyze the relationship between bike availability and POI characteristics.
- Used the 'statsmodels' module to build the regression model.
- Interpreted the model results and derived insights.
- Applied Principal Component Analysis (PCA) to reduce dimensionality and improve model performance.
- **Challenges**: Ensuring the model's validity and interpreting the results accurately.
- 
![bike availability](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/514f69f6-8da6-4dcd-9e9e-3c1603b11b26)


### Part 5: Visualization and Interpretation 📊

**Task Overview**:
- Created various visualizations to interpret the model results.
- Generated bar plots and scatter plots to visualize relationships between bike availability and specific POIs.
- **Challenges**: Ensuring the visualizations were clear and conveyed the intended insights effectively.

![bike](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/e6a2b76d-5de3-46b0-a765-efc2572d91d7)

![bike](https://github.com/Asal-zou/Statistical-Modelling-Project/assets/134029102/451355d7-9c9b-48c2-bb18-8e090f45202f)


## Results 📈

- **Significant Findings**:
  - Parks have a significant effect on the model based on their p-value.
  - The R and R-squared values were very low, indicating that POIs didn't have much effect on bike availability in general.
  - Insights suggest that factors other than POIs may play a larger role in bike availability.

## Challenges ⚠️

- **Data Retrieval**: Retrieving accurate information about POIs directly from APIs was difficult due to varying data quality and coverage.
- **Data Integration**: Merging data from different sources and ensuring consistency was challenging.
- **Model Performance**: The low R-squared values indicated that the model might need more features or a different approach.

## Future Goals 🚀

- **Enhanced Data Collection**: Collect more comprehensive data, possibly including additional features such as weather, time of day, and demographic information.
- **Model Improvement**: Explore different modeling techniques and features to improve the R and R-squared values.
- **Deeper Analysis**: Conduct a deeper analysis of other potential factors influencing bike availability, such as socio-economic factors and traffic patterns.
- **Automation**: Automate the data collection and preprocessing steps to ensure up-to-date analysis.
