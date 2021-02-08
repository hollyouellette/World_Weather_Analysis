# World Weather Analysis

This repository contains a three-part analysis:

1. **Retrieve Weather Data**
 
      This was accomplished by generating 2000 random lantitudes and longitudes and then identifying the nearest city to those coordinates using the _citipy_ module. Next, we performed an API call with OpenWeatherMap to retrieve the following             information:<br/><br>
                 - Latitude and longitude<br>
                 - Maximum temperature<br>
                 - Percent humidity<br>
                 - Percent cloudiness<br>
                 - Wind speed<br>
                 - Weather description (for example, clouds, fog, light rain, clear sky)<br>
      Finally, this information was input into a dataset that was exported to a CSV file.
      
      This file can be found in the <a href="https://github.com/hollyouellette/World_Weather_Analysis/tree/main/Weather_Database">Weather_Database Folder</a> saved as **WeatherPy_Database.csv**.
      
2. **Create a Customer Travel Destinations Map**
   
     Next, the data from the WeatherPy_Database.csv was used to creat a new dataframe that showcases the nearest hotel to each city cased on it's longitude and latitude. Using the Google Maps API, we generated a map with pop-up makers to showcase the Hotel Name, City, County & Current Weather Description with Maximum Temperature for each location.
     
     This analysis, in addition to the image below, can be found in the <a href="https://github.com/hollyouellette/World_Weather_Analysis/tree/main/Vacation_Search">Vacation_Search Folder</a> of this repository.
     
     <img src="https://github.com/hollyouellette/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png">
     
   
