**# World_Weather_Analysis**


**## Project Overview** 

PlanMyTrip is a top travel technology company specialized in internet related services in the hotel and lodging industry. This Analysis will help the user interface and functionalities of the PlanMyTrip app with filtering potential travel destinations worldwide, accessing weather data including the weather description for over 500 cities across the world, creating a customer travel destinations map, and a travel itinerary map.


**### Resources:**

**Software:** Python 3.9.7, Anaconda 4.10.3, Jupyter Notebook 6.4.5

****Data Source:**

*Google Maps Directions API :[(https://developers.google.com/maps/documentation/directions/overview)]

*Jupyter-gmaps: [(https://jupyter-gmaps.readthedocs.io/en/latest/)]

*citipy: [(https://github.com/wingchen/citipy)]

*Google Maps and Places API: [(https://jupyter-gmaps.readthedocs.io/en/latest/)]

*OpenWeatherMap API: [(https://openweathermap.org/current)]

****Results

A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.
The following data was retrieved from the API call:
Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Current Weather description

Vacation Search
Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

The Travel App allows customers to search for locations they want to travel based on their temperature preferences: Once the customers have filtered the database (DataFrame) based on their temperature preferences, a heatmap will be showed to them for the maximum temperature for the filtered cities around the world.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/101952961/168619488-1f5f05ed-d8c0-437f-917d-021d974f3ff0.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/101952961/168619607-47fc2d5e-2ca1-4116-815e-ba0457c92dc9.png)

Statistical Analysis
Global city data was plotted, and linear regression was used to find the relationship between the following variables:

Latitude and Maximum Temperature
Latitude and Humidity
Latitude and Cloudiness
Latitude and Wind Speed

![Fig1](https://user-images.githubusercontent.com/101952961/168620115-01a648ad-78b3-440d-936c-249e7c03cf3c.png)

![Fig2](https://user-images.githubusercontent.com/101952961/168620187-fda450ed-7910-4e49-932a-d71ece7bec8c.png)

![Fig3](https://user-images.githubusercontent.com/101952961/168620292-82b4de95-3329-449e-a612-46f017d0de12.png)

![Fig4](https://user-images.githubusercontent.com/101952961/168620367-102dab9e-5758-430b-bb11-4b99a3b38693.png)





