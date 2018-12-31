# WeatherPy
![Temp plot](https://github.com/ejhagee/Python-Data-Visualization-Projects/blob/master/WeatherPy/Resources/Temperature_Plot.png)

## Description
This project investigates how different latitudes result in various weather measurments such as latitude, wind speed, humidity, and cloud cover.  It appears that the main difference observed is in temperature, while any trends in the other three are small at most.

## Approach and File Structure
 - PythonAPI tools uses the Requests library to access the weather of various cities on September 14, 2018.  The dependence of various factors on latitude is investigated.
 - Data is retrieved from the Open Weather API, found at https://openweathermap.org/api
 - The citipy library is also used.  Documentation can be found at https://github.com/wingchen/citipy
 - The code is contained in the jupyter notebook WeatherPy.ipynb.
 - The Resources folder contains various saved data and images.  The cities.csv file contains the raw data accessed from the API.  As well, plots displaying outcomes such as wind speed and the maximum temperature are also included.
 - The results are also displayed at https://ejhagee.github.io/WeatherPy-WebPage/
