# World_Weather_Analysis

PlanMyTrip app is a top travel technology company that specializes in internet related services in the Hotel and Lodging industry. Jack is the head of analysis for the user interface team. Objective of the analysis is to help Jack to collect and present data for customers based on their preferred criteria. The final purpose of this project is to recommond a travel itinerary of four cities to users.

There are three sections in this project:

## 1.	Create Weather Database

A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.

The following data was retrieved from the API call:

Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Current Weather description


Finally,  gathered information was put  into a DataFrame and exported to a csv file.

The [Weather_DataBase.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Weather_Database/Weather_Database.ipynb) file

The [WeatherPy_Database.csv](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Weather_Database/WeatherPy_Database.csv) file


## 2.	Vacation Search
Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

The [Vacation_Search.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/Vacation_Search.ipynb) file

The [WeatherPy_vacation.csv](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/WeatherPy_vacation.csv) file

The [WeatherPy_vacation_map.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Search/WeatherPy_vacation_map.png) image


## 3.	Vacation Itinerary
-	 Finally, four cities in Canada were chosen to create a final travel itinerary. Start & end: Shelburne; stop1: Jamestown; stop2: Havre-Saint-Pierre; stop3: Chapais.
-	 By using the Google Maps Directions API, I created a travel route by driving between the four cities within marker layer map.
-	 Lastly, map with marker and info box for only these four cities was created and exported.

The [Vacation_Itinerary.ipynb](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/Vacation_Itinerary.ipynb) file

The [WeatherPy_travel_map.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/WeatherPy_travel_map.png) image

The [WeatherPy_travel_map_markers.png](https://github.com/weihaolun/world-weather-analysis/blob/a8e09f4cd1b3d400c020d4bb94238d93a755e377/Vacation_Itinerary/WeatherPy_travel_map_markers.png) image
