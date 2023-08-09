
VacationPy.ipynb and WeatherPy.ipynb are two assigments due for the Module 6 homework for the U fo MN Bootcamp.

The WeatherPy code generates a list of 1,500 random lat and long coordinates and then finds the nearest cities to those coordinates. Many duplicate cities are found and in the end there are roughly 600 cities gathered.  

Then data from the OpenWeatherMap API is gathered and put into a pandas DataFrame, the 'Date' column is converted to a more understandable format and the temperature is converted from Kelvin to Celsius. I used stackoverflow.com and sparkbyexamples.com to reference while formulating those codes to convert those columns. More specific URLs are listed in the file. 

Scatter plot and linear regressions are then created off of various data in the data sets. Each linear regression graph is labeled with the equation of the line and the r-values. 

The VacationPy.ipynb code looks at a csv file and displays the data on a map. Next the cities are narrowed down by ideal weather. Then a new dataset is created by adding the nearest hotel locations to those cities using the Geoapify API. Then the narrowed list of data is remapped, this time also including the hotel name and country in the hover message. 

