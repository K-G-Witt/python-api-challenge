# python-api-challenge
Data from over 500 cities worldwide were compared on maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), Wind Speed (m/s). 


## Project Description:
This program consists of two, related projects:

1. **WeatherPy:** program to explore the relationship between city latitude and the above weather variables.
   
2. **VacationPy:** program to filter the above cities by user-defined preferences for maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), and Wind Speed (m/s) and to provide the hotel name and address of the nearest hotel for these cities.


## Installation and Run Instructions:
1. Before running this program, users will need to register for an API key from:
   (i) **OpenWeatherMap API:** https://openweathermap.org/api
   (ii) **Geoapify:** url: https://www.geoapify.com/


2. Next, you will need to supply your own **weather_api_key** and **geoapify_key** in the **config.py** files.

 
3. Following this, executing the script provided in the **WeatherPy** Jupyter Lab Notebook will output the following information:
   (i) Scatter plot of latitude vs. maximum temperature (C)
   (ii) Scatter plot of latitude vs. humidity (%)
   (iii) Scatter plot of latitude vs. cloudiness (%)
   (iv) Scatter plot of latitude vs. wind speed (m/s)
   (v) Regression plot of latitude vs. temperature (C), Northern Hemisphere
   (vi) Regression plot of latitude vs. temperature (C), Southern Hemisphere
   (vii) Regression plot of latitude vs. humidity (%), Northern Hemisphere
   (viii) Regression plot of latitude vs. humidity (%), Southern Hemisphere
   (ix) Regression plot of latitude vs. cloudiness (%), Northern Hemisphere
   (x) Regression plot of latitude vs. cloudiness (%), Southern Hemisphere
   (xi) Regression plot of latitude vs. wind speed (m/s), Northern Hemisphere
   (xii) Regression plot of latitude vs. wind speed (m/s), Southern Hemisphere

 
4. Executing the script provided in the **VacationPy** Jupyter Lab Notebook will output the following information:
   (i) Map of every city
   (ii) A filtered dataframe of cities selected by user-defined preferences for maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), and Wind Speed (m/s)
   (iii) A dataframe to hold information on the hotel name and address of the nearest hotel for these cities
   (iv) Map of every city in the filtered dataframe, along with hotel information (name, address) in accompanying hover messages


## Credits:
This code was compiled and written by me for the pymaceuticals challenge class homework in the 2024 Data Analytics Boot Camp hosted by Monash University. 
