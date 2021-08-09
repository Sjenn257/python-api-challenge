# python-api-challenge
Python API Homework - What's the Weather Like?

Using OpenWeatherMap API, I have analyzed 500+ cities across the world of varying distance from the equator to create a representative model of weather across the world. It includes Temperature, Humidity %, Cloudiness %, and Wind Speed. Then I created a heatmap of humidity % of these cities.

WeatherPy

In studying the scatter plots of the cities' in relation to their distance from the equator, my analysis showed a positive correlation to temperature the closer they are to the equator. Humidity % and Cloudiness % exists across the board but appears to be more dense in the northern hemisphere. Windspeed did not show a correlation relative to its distance from the equator.

VacationPy

In this analysis, I extracted cities with my ideal weather in mind.
  - Temperature between 70 and 90 degrees
  - Humidity less than 20%
  - Cloudiness less than 5%
  - Wind Speed less than 10mph

Then, using Google API, I found the nearest hotel based on their lat/longs for each city. There are 5 of cities that match!

Finally, I created a heatmap of all the cities used in WeatherPy to represent the humidity across the world and plotted the hotels for my 5 ideal vacation spots!

