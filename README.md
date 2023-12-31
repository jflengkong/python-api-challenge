# Python API Challenge 
## Week 6 - UWA Challenge 

This challenge allows us to show that data has true power in that it is able to definitively answer questions. The question we ask today is "What is the weather like as we appropach the equator?"
These codes allow us to prove simple questions such as this.  This deliverable will find us creating a Python Script to visualise the weather of over 500 cities of varying distances from the equator. The [citipy Python Library](https://pypi.org/project/citipy/) and [OpenWeatherAPI](https://openweathermap.org/api) will be used to create a representative model of weather across cities. 

We used the following Dependencies: 

![dependencies](https://github.com/jflengkong/python-api-challenge/blob/main/Screenshots/dependencies.png)

This repository will show the following: 

## Part 1: WeatherPY 
Note all screenshots will vary dependent on each random latitude and longitude provided by each random generator and of which date the kernel was run. These screenshots are provided as examples. 
1. Plots to showcase the Relationship Between Weather Variables and Latitude: 
    - Latitude vs. Temperature
    - ![Lat vs. Temp](https://github.com/jflengkong/python-api-challenge/blob/main/output_data/Fig1.png)
    - Latitude vs. Humidity
    - ![Lat vs. Humidity](https://github.com/jflengkong/python-api-challenge/blob/main/output_data/Fig2.png)
    - Latitude vs. Cloudiness
    - ![Lat vs. Cloudiness](https://github.com/jflengkong/python-api-challenge/blob/main/output_data/Fig3.png)
    - Latitude vs. Wind Speed
    - ![Lat vs. Wind Speed](https://github.com/jflengkong/python-api-challenge/blob/main/output_data/Fig4.png)
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
Weather data skills put to the test to plan future vacations. [Hvplot](https://pypi.org/project/hvplot/) library was be used with Geoviews. The following were completed: 
1. A map that displays a point for every city in the city_data_df create in WeatherPy.
   ![map hotel](https://github.com/jflengkong/python-api-challenge/blob/main/Screenshots/hotel_df.png)
2. A dataframe called hotel_df that includes my ideal weather conditions (below 25 degrees C and less than 40% Humidity)
3. Completed hotel_df with the first hotel located within 10,000 metres of the coordinates of each city in hotel_df
   ![hotel_df](https://github.com/jflengkong/python-api-challenge/blob/main/Screenshots/hotel_df_df.png)
4. Add the hotel name and country as additional information in the hover message for each city in the map.
   ![map](https://github.com/jflengkong/python-api-challenge/blob/main/Screenshots/map.png)




