# python-api-challenge

## Description
Used a python script and matplotlib to:
1) Analyze the weather of 500+ cities across the world of varying distance from the equator using OpenWeatherMap API. Analyzed data to showcase relationships between temperature, humidity, cloudiness, windspeed and latitude across cities. Ran a linear regression to see if there was correlation between these factors in Northern or Southern Hemispheres.
2) Analyze lodging from Google Places API to find an ideal vacation city (located within 5000 meters of coordinates). Plotted hotels on top of a heatmap with each pin containing the Hotel Name, City, and Country.


## Instructions
Please use below links to view:
1) WeatherPy notebook: [Link](https://nbviewer.jupyter.org/github/laurenemilyto/python-api-challenge/blob/main/WeatherPy/WeatherPy.ipynb)
2) VacationPy notebook: [Link](https://nbviewer.jupyter.org/github/laurenemilyto/python-api-challenge/blob/main/VacationPy/VacationPy.ipynb)


## Insights from WeatherPy Analysis:
- Temperature and Latitude have a positive relationship in the Southern Hemisphere. As a city's latitude increases, its temperature does as well. In the Northern Hemisphere, Temperature and Latutitude have a negative relationship. As a city's latitude decreases, temperature also decreases. Therefore, Latitude and Temperature are strongly correlated. 
- Looking at the relationship between Temperature and Latitude, the Northern Hemisphere has a slightly lower r-squared value (0.626) than the Southern Hemisphere (0.783). This means there is a higher percentage of variance across Northern cities and their temperatures, perhaps due to the fact 3x more cities are located North of the Equator in the dataset.
- Temperature, Humidity, Cloudiness and Wind Speed are not strongly correlated with Latitude. Looking at linear regressions between variables, one can see that the line of best fit shows a weak relationship. There are also a number of major outliers within each linear regression.


