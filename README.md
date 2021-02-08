#World Weather Analysis

This repository contains a three-part analysis:

1. **Retrieve Weather Data**
 
      This was accomplished by generating 2000 random lantitudes and longitudes and then identifying the nearest city to those coordinates using the _citipy_ module. Next, we performed an API call with OpenWeatherMap to retrieve the following             information:<br/><br>
                 - Latitude and longitude<br>
                 - Maximum temperature<br>
                 - Percent humidity<br>
                 - Percent cloudiness<br>
                 - Wind speed<br>
                 - Weather description (for example, clouds, fog, light rain, clear sky)<br>
