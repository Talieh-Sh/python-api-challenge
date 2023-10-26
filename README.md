# python-api-challenge: Weatherby and VactionPy

## Background
This project aims to answer: " What is the weather like as we approach the equator?" You may say that it is evident that the weather is getting hotter as you approach the equator but the purpose of this project aims to provide more evidence for that and uncover other weather trends and patterns.

## Repository Structure
WeatherPy.ipynb:        Jupyter notebook for the WeatherPy analysis(in WeatherPy folder)

VacationPy.ipynb:       Jupyter notebook for the VacationPy analysis(in WeatherPy folder)

.gitignore:             To ignore specific files like api_keys.py

## Part1:WeatherPy
the WeatherPy notebook dives into the analysis of weather trends across about 500 cities at various distances from the equator. The analysis is based on the data fetched from the OpenWeatherMap API.

## Analysis and Visualizations:
1- Scatter plots showing the relationship between:

   - Latitude vs. Temperature
    
   - Latitude vs. Humidity
    
   - Latitude vs. Cloudiness
    
   - Latitude vs. Wind Speed

2- Linear regression models to examine the above relationships, split by Northern and Southern Hemispheres.
    
## Part2: VacationPy
The VacationPy notebook employs the Geoapify API and geoviews Python library to provide map visualization. it helps plan vacations based on the weather.

## Features:
- A map displaying the points for each city, with the point size representing humidity

- Filtering cities based on ideal weather conditions.

- Extracting hotels within 10,000 meters of the city coordinates.

- By hovering around each city points related informations are displayed


## Dependencies and Libraries
Python

Jupyter Notebook

pandas

matplotlib

citipy


## APIs
OpenWeatherMap API

Geoapify API
