# data-mining-project-
This is my project for the Data Mining course


## Description
This project demonstrates the data preprocessing, merging, and analysis of bike rental datasets in San Jose. The project includes:
- Cleaning and preprocessing trip, weather, and station data using PySpark.
- Merging datasets to create a unified dataset.
- Implementing a PageRank algorithm for analysis.

## Data
Data come from a company which has collected information on the stations, trips taken, and on weather conditions in San Francisco and other cities from September 2014 to August 2015.
The following datasets are used in this project, all publicly available on [Bay Area Bike Share Open Data](https://bayareabikeshare.com/open-data):

1. **Trip Data**:
   - Contains details about bike trips, including start and end dates, stations, and user types.
2. **Weather Data**:
   - Includes weather conditions during the trip periods.
3. **Station Data**:
   - Provides information about bike rental stations.

### **1. Station Information**
Provides information about bike rental stations.
- **Variables**:
  - `Id`: Station ID number.
  - `Name`: Name of the station.
  - `Lat` / `Long`: Latitude and longitude of the station.
  - `Dock Count`: Total number of docks at the station.
  - `City`: The city where the station is located (e.g., San Francisco, San Jose).

### **2. Trip Data**
This dataset contains detailed information about bike trips, including start and end stations.
- **Variables**:
  - `Trip ID`: Unique numeric identifier for each trip.
  - `Duration`: Time of trip in seconds.
  - `Start Date` / `End Date`: Start and end timestamps of the trip in PST.
  - `Start Station` / `End Station`: Station IDs for trip start and end.
  - `Subscription Type`: Subscriber type (annual or short-term customer).

### **3. Daily Weather Measurements**
This dataset includes daily weather conditions in the regions where bike stations are located.
- **Variables**:
  - `Date`: The date of the recorded weather.
  - `Temperature`: Minimum, mean, and maximum daily temperatures (°F).
  - `Dew Point`: Minimum, mean, and maximum daily dew point temperatures (°F).
  - `Humidity`: Daily minimum, mean, and maximum humidity (%).
  - `Pressure`: Daily minimum, mean, and maximum atmospheric pressure (inHg).
  - `Visibility`: Daily minimum, mean, and maximum visibility (miles).
  - `Wind Speed`: Maximum and mean daily wind speeds (mph).
  - `Precipitation`: Total daily precipitation (inches).
  - `Cloud Cover`: Scale from 0 (clear) to 8 (totally covered).
  - `Events`: Special meteorological events (e.g., rain, fog).
  - `Zip`: Zip code corresponding to the city.