# python-api-challenge
The purpose of this project is to pull weather data from an API for randomized cities and then use that data for statistical analysis. That same data is then filtered by ideal weather conditions and the remaining locations are used to find hotels in the local area.
This repository holds 2 jupyter notebook files as well as image files exported from the first "Weather" notebook file. It also contains a csv of the randomized cities generated.

The following code was devised from: https://www.w3schools.com/python/matplotlib_grid.asp
plt.grid()

https://www.w3schools.com/python/python_functions.asp
def LReg(x,y):

https://stackoverflow.com/questions/34682828/extracting-specific-selected-columns-to-new-dataframe-as-a-copy
hotel_df = filtered_city_data_df[['City','Country', 'Lat', 'Lng','Humidity']].copy()
