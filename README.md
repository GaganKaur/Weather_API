This code makes use of the citipy library and the Open weather Map API requests to get the weather data across multiple cities globally.

In the first part of the code, we geneate 2000 random floating values between +-90 for latitude and longitudes respetively.

We then use the citipy library to finf the nearest city names with their country codes corresponding to each latitude and longitude set.
These names of cities are then stored in a csv file.

We then make use of OWM API to get the weather data for each of these cities and extract their latitudes, the maximum temperature, humidity and the cloudiness at that locations.

We then plot four scatter plots to study the dependence of temperature, humidity, cloudiness and wind speed on latitides respectively.

"Test"
