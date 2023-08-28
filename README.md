# python-api-challenge
Week 6 - UWA Challenge 

This challenge allows us to show that data has true power in that it is able to definitively answer questions. The question we ask today is "What is the weather like as we appropach the equator?"
These codes allow us to prove these simple questions. This deliverable will find us creating a Python Script to visualise the weather of over 500 cities of varying distances from the equator. The [citipy Python Library](https://pypi.org/project/citipy/) and [OpenWeatherAPI](https://openweathermap.org/api) will be used to create a representative model of weather across cities. 

We used the following Dependencies: 

![dependencies]()

import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import requests
import time
from scipy.stats import linregress

This repository will show the following: 

##Part 1: WeatherPY 
1. Plots to showcase the Relationship Between Weather Variables and Latitude: 
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
2. Linear regression for Each Relationship into Northern vs. Southern Hemisphere including the following plots:
    - Northern Hemisphere: Temperature (C) vs. Latitude
    - Southern Hemisphere: Temperature (C) vs. Latitude
    - Northern Hemisphere: Humidity (%) vs. Latitude
    - Southern Hemisphere: Humidity (%) vs. Latitude
    - Northern Hemisphere: Cloudiness (%) vs. Latitude
    - Southern Hemisphere: Cloudiness (%) vs. Latitude
    - Northern Hemisphere: Wind Speed (m/s) vs. Latitude
    - Southern Hemisphere: Wind Speed (m/s) vs. Latitude
      
## Part 2: VacationPy  
Weather data skills put to the test to plan future vacations. [Hyplot](https://pypi.org/project/hvplot/) library was be used with Geoviews. The following were completed: 
1. A map that displays a point for every city in the city_data_df create in WeatherPy.
2. A dataframe called hotel_df that includes my ideal weather conditions (below 25 degrees C and less than 40% Humidity)
3. Completed hotel_df with the first hotel located within 10,000 metres of the coordinates of each city in hotel_df.
4. Add the hotel name and country as additional information in the hover message for each city in the map.




