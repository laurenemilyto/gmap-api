# python-api-challenge

## Description
Used a python script and matplotlib to:
1) Analyze the weather of 500+ cities across the world of varying distance from the equator using OpenWeatherMap API. Analyzed data to showcase relationships between temperature, humidity, cloudiness, windspeed and latitude across cities. Ran a linear regression to see if there was correlation between these factors in Northern or Southern Hemispheres.
2) Analyze lodging from Google Places API within ideal vacation city (located within 5000 meters of coordinates). Plotted hotels on top of a heatmap with each pin containing the Hotel Name, City, and Country.



## Instructions
Please use this link to view the:
1) WeatherPy notebook: 
2) VacationPy notebook:


## Insights from WeatherPy Analysis:
- Temperature and Latitude have a positive relationship in the Southern Hemisphere- as a city's latitude increases, its temperature does as well. In the Northern Hemisphere, Temperature and Latutitude have a negative relationship- as a cities latutitude decreases, temperature also decreases. Lat and temp are strongly correlated in both hemispheres. The Northern Hemisphere has a slightly smaller r-squared value than the Southern Hemisphere. This means that there is a slightly higher percentage of variance in the Northern Hemisphere, and likely due to the fact that 3x more cities are located North of the Equator in the dataset.
- Temperature and Humidity do not have a strong correlation in either Hemisphere. The fit is weak and there are a large number of major outliers in the dataset. 
- Temperature and Wind Speed do not have a strong correlation in either Hemisphere. The fit is weak and there are a large number of major outliers in the dataset. 


