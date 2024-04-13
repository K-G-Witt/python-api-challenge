# python-api-challenge
Data from over 500 cities worldwide were compared on maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), Wind Speed (m/s). 


## Project Description:
This program consists of two, related projects:

1. **WeatherPy:** program to explore the relationship between city latitude and the above weather variables.
   
2. **VacationPy:** program to filter the above cities by user-defined preferences for maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), and Wind Speed (m/s) and to provide the hotel name and address of the nearest hotel for these cities.


## Installation and Run Instructions:
Before running this program, users will need to register for an API key from:
1. **OpenWeatherMap API:** https://openweathermap.org/api
2. **Geoapify:** url: https://www.geoapify.com/

 
Following this, executing the script provided in the **WeatherPy** Jupyter Lab Notebook will output the following information:
1. Scatter plot of latitude vs. maximum temperature (C)
2. Scatter plot of latitude vs. humidity (%)
3. Scatter plot of latitude vs. cloudiness (%)
4. Scatter plot of latitude vs. wind speed (m/s)
5. Regression plot of latitude vs. temperature (C), Northern Hemisphere
6. Regression plot of latitude vs. temperature (C), Southern Hemisphere
7. Regression plot of latitude vs. humidity (%), Northern Hemisphere
8. Regression plot of latitude vs. humidity (%), Southern Hemisphere
9. Regression plot of latitude vs. cloudiness (%), Northern Hemisphere
10. Regression plot of latitude vs. cloudiness (%), Southern Hemisphere
11. Regression plot of latitude vs. wind speed (m/s), Northern Hemisphere
12. Regression plot of latitude vs. wind speed (m/s), Southern Hemisphere

 
Executing the script provided in the **VacationPy** Jupyter Lab Notebook will output the following information:
1. Map of every city
2. A filtered dataframe of cities selected by user-defined preferences for maximum daily temperature (degrees Celsius), humidity (%), Cloudiness (%), and Wind Speed (m/s)
3. A dataframe to hold information on the hotel name and address of the nearest hotel for these cities
4. Map of every city in the filtered dataframe, along with hotel information (name, address) in accompanying hover messages


## Credits:
This code was compiled and written by me for the pymaceuticals challenge class homework in the 2024 Data Analytics Boot Camp hosted by Monash University. 
