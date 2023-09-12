# python-api-challenge1
Summary:

​

Selection of days for the vacation is challenging depend on the weather.

First to find the coordinates of the place and to find the nearest hotels surrounding that coordinates used by Geopify API key.

Here I used Citypy  python library (https://pypi.python.org/pypi/citipy) and  open weather map API (https://openweathermap.org/api). I created plots to showcase the relationship between weather variables and latitude.

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Computed the linear regression for each relationship and Next, create a series of scatter plots and  included the linear regression line, the model's formula, and the r values as we can see in the image.

Use this deliverables to plan the vacation place.

Created a map that displays a point for every city in the city_data_df , DataFrame as shown in the image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness

Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
