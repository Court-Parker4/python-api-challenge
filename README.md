# python-api-challenge
What is the weather like as we approach the equator?
----------------------------------------------
## Part I - WeatherPy
Showcases a series of scatter plots to the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Second set of reports show the run of linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
-------------------------------------------------------------------
## Part II - VacationPy
Utilize weather data to plan future vacations.
First Heat map
1. Create a heat map that displays the humidity for every city from the part I
Second heat map
2. Dataframe is narrow down to display ideal vacation temperature destinations:
* A max temperature lower than 80 degrees but higher than 70.
* Wind speed less than 10 mph.
* Zero cloudiness.
Third Heat Map
3. Nearest hotel locations are added and displayed 
