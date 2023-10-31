# python-api-challenge
Module 6 - Python API challenge

**WeatherPy**

For this challenge deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library and the OpenWeatherMap API to create a representative model of weather across cities.

_Requirement 1_

I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code and created the following scatter plots for the relationships between:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

_Requirement 2_

I computed the linear regression for each relationship above. Then, I created scatter plots for the following Northern and Southern Hemispheres which included their linear regression lines, model's formula, and the r-values:
* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

**VacationPy**

For this challenge deliverable, I created a Python script to develop map visualizations to plan future vacations using Jupyter notebooks, geoViews Python library, and Geoapify API.

_Requirements_

1. Created a map that displays a point for every city in the city_data_df DataFrame with all sizes of the city points equal to the city's humidity percentage.
2. Narrowed down the city_data_df Data frame to my ideal weather conditions of:
* Temperature between 70 and 80 degrees Fahrenheit
* Wind speed less than 10 mph
* Cloudiness of less than 10%
3. Created a new hotel_df DataFram to store the city, country, coordinates, and humidity for the cities
4. Used Geoapify API to find the first hotel located within a 16100-meter (10-mile) radius for each city
5. Added the hotel name and country to the hover message for each city on a map

**Resources and References**

During the challenge, I referenced the following to aid in my understanding and completion of the assignment:

1. Reviewed and reperformed a majority of the class activites in my GitLab Working Folder
2. Watched the following Dr. A instructor videos:
* [APIs Day 02 - Activity 03 - OpenWeatherMap API Setup and Requests Demo](https://www.youtube.com/watch?v=Y9rAlwlP7hs)
* [APIs Day 02 - Activity 05 - OpenWeatherMap DataFrame Demo](https://www.youtube.com/watch?v=nMSUPm5e-3c)

I also performed additional online research to gain more understanding of the following topics:

* [OpenWeather Current Weather Data API Documentation](https://openweathermap.org/current)
* [Geoapify API Docs](https://apidocs.geoapify.com/docs/places/#about)

