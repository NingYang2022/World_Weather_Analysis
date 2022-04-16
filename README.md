# World_Weather_Analysis
## <font color=#6495ED>Background</font>
We need to create codes to add the weather description to the weather data  we already retrieved from https://openweathermap.org/. Then, we'll use input statements to filter the data for the weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, we will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.
## <font color=#6495ED>Purposes</font>
Retrieve Weather Data
* Create a new set of 2,000 random latitudes and longitudes
* Get the nearest city using the citipy module
* Retrieve the following information from the OpenWeatherMap API call:
    -	Latitude and longitude
    -	Maximum temperature
    -	Percent humidity
    -	Percent cloudiness
    -	Wind speed
    -	Weather description ( clouds, fog, light rain, clear sky)

Create a Customer Travel Destinations Map
* Use input statements to prompt the customer for their minimum and maximum temperature preferences
* Use the preferences to identify potential travel destinations and nearby hotels
* Show the destinations on a marker layer map with pop-up markers for the cities that have the following information:
    -   Hotel name
    -	City
    -	Country
    -	Current weather description with the maximum temperature.

Create a Travel Itinerary Map
* Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. 
* Create a marker layer map with a pop-up marker for each city on the itinerary.

## <font color=#6495ED>Resources</font>
* Data Source:
    * OpenWeatherMap API
    * Google Map API
* Software: Python3.9, Anaconda3, Jupyter Notebook


## <font color=#6495ED>Results</font>
- We get DataFrame information from the OpenWeatherMap API call
![WeatherPy_Database_df](https://github.com/NingYang2022/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database_df.png?raw=true)
- We create a marker layer map that shows the destinations  with pop-up markers for the cities

![WeatherPy_vacation_map](https://github.com/NingYang2022/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png?raw=true)
- We use Google Directions API to create a travel itinerary that shows the route between four cities
![WeatherPy_travel_map](https://github.com/NingYang2022/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png?raw=true)
- We create a marker layer map with a pop-up marker for each city on the itinerary.
![WeatherPy_travel_map_marker](https://github.com/NingYang2022/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_marker.png?raw=true)

