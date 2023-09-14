Python API Basics 
-------
Part I
-------
In this example using Jupyter Notebook, I create a Python script to visualize the weather of over 500 cities of varying distances from the equator, using OpenWeatherMap API to retrieve weather data from the cities. 

I created a series of scatter plots to showcase the following relationships and compute the linear regression for each relationship:

* Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

Part II
-------
Additionally, I use the geoViews Python library, and the Geoapify API to create a map that displays a point for every city, with the size of the point the humidity in each city.\

After specifying specific criteria, I used the Geoapify API to find the first hotel located within 10,000 meters that match the criteria, and added the hotel name and the country as additional information in the hover message for each city on the map.

