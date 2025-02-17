# WeatherApp

##Description:
This program calls free public APIs to get weather data and returns a human readable description of the forcast to the terminal. The two APIs that I used are:
* [National Weather Service API] (https://weather-gov.github.io/api/general-faqs)
* [US Census Geocoder API] (https://geocoding.geo.census.gov/geocoder/Geocoding_Services_API.html)

I chose to use these APIs because they are free to use to the public which makes this code more accessible. The expected order of x,y or {Longitude},{Latitude} coordinates for the two APIs is opposite, which makes the code somewhat difficult to follow. Keep in mind that when switching from the US Census Geocoder API to the National Weather Service API, the coordinates need to be reversed. I plan to add a desktop implementation to this project with a system tray icon feature in the future. 


##How to run:
To run this you will need python3 installed on your system, as well as the PyPi package **requests**. 
You can install requests using the following command after you have installed python3.
```$ python -m pip install requests```
If you run into any issues with missing python modules, refer to the requirements.txt.

Each module can be run on its own allowing them to be used in other projects as helper functions. To run the project as a whole, run **weather_app.py** and enter a full US address.

##More information on the APIs can be found here:
*[https://geocoding.geo.census.gov/geocoder/] (https://geocoding.geo.census.gov/geocoder/)
*[https://www.weather.gov/documentation/services-web-api] (https://www.weather.gov/documentation/services-web-api)

#Legal info:
This program is free to use under the MIT license.
