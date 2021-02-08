# World Weather Analysis

This repository contains a three-part analysis of weather from randomly selected global coordinates. This was completed over three main steps:

1. **Retrieve Weather Data**
 
      This was accomplished by generating 2000 random latitudes and longitudes and then identifying the nearest city to those coordinates using the _citipy_ module. Next, we performed an API call with OpenWeatherMap to retrieve the following             information:<br/><br>
                 - Latitude and longitude<br>
                 - Maximum temperature<br>
                 - Percent humidity<br>
                 - Percent cloudiness<br>
                 - Wind speed<br>
                 - Weather description (for example, clouds, fog, light rain, clear sky)<br>
      
      Finally, this information was input into a dataset that was exported to a CSV file.
      
      This file can be found in the <a href="https://github.com/hollyouellette/World_Weather_Analysis/tree/main/Weather_Database">Weather_Database Folder</a> saved as **WeatherPy_Database.csv**.
      
2. **Create a Customer Travel Destinations Map**
   
     Next, the data from the WeatherPy_Database.csv was used to create a new dataframe that showcases the nearest hotel to each city based on it's longitude and latitude coordinates. Using the Google Maps API, we generated a map with pop-up markers to showcase the Hotel Name, City, Country & Current Weather Description with Maximum Temperature for each location.
     
     This analysis, in addition to the image below, can be found in the <a href="https://github.com/hollyouellette/World_Weather_Analysis/tree/main/Vacation_Search">Vacation_Search Folder</a> of this repository.
     
     <img src="https://github.com/hollyouellette/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png">
     
3. **Create a Travel Itinerary Map**

     Finally, using the csv output from the previous step, we created a marker layer map of the vacation search results. From here, we selected the 4 cities that a customer might want to visit. Using gmaps documentations, we created a directions layer map to identify and highlight a driving route that connects all 4 trip stops. 

 <img src= "https://github.com/hollyouellette/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png">
 
 As a last step, we added pop-up markers for each city to highlight the Hotel, City Name, Country and Weather of that destination. 
 
 <img src= "https://github.com/hollyouellette/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png">
 
 These images as well as their detailed code can be found the in the <a href="https://github.com/hollyouellette/World_Weather_Analysis/tree/main/Vacation_Itinerary">Vacation_Itinerary Folder</a> of this repository.
