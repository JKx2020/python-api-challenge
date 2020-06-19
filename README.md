# Python-API-Challenge
This project has two parts:

Part 1: I created a Python script to visualize the weather of 500+ cities across the world using a python citipy library https://pypi.python.org/pypi/citipy) and OpenWeatherMap API (https://openweathermap.org/api). 

I use the following libraries in this project:
  * citipy
  * pprint
  * pandas
  * matplotlib.pyplot
  * numpy
  * random
  * decimal
  * requests
  * from time import sleep
  * from scipy import stats

I first randomly select 500 unique cities based on latitude and longitude and perform a weather check on :
1. Scatter plots to show:
  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude
2.Run linear regression analysis on different weather attributes and weather it's southern or northern hemishpere city

Part 2: I use gmaps and Google Places API to write a scipt to help plan future vacations based on your weather preferences. This part of the project looks at all the cities and their weather data and narrows them down to the weather of your choice. At the end you get a list of possible vacation citites and the nearest hotel to that latitude and longitude based on your preferred weather. I use Google Places API to find the first hotel for each city located within 5000 meters of your coordinates and plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.


To run this project:
1. go to WeatherPY/weatherpy.ipynb and run that script first
2. after the "weatherpy.ipynb" script runs completely, then go to ../VacationPy/vacationpy.ipynb and run that script
3. the scripts will generate PDF files that are graphs created when the scripts run in both VacationPY and WeatherPY
4. the CSV files in the WeatherPY and VacationPY folders are dataframes created when running the scripts
5. the final outputs for this project are in the VacationPY folder and give you a list of cities with your ideal weather and the hotels closest to those cities latitude and longitude coordinates:
 * "city_perfect_weather.csv"
 * "hotel_df.csv"

<strong>Please reference my "Web-Design-Challenge" repository to see this project as a webpage: https://github.com/JKx2020/Web-Design-Challenge<strong>
