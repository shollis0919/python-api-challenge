# python-api-challenge
The purpose of this project is to pull weather data from an API for randomized cities and then use that data for statistical analysis. That same data is then filtered by ideal weather conditions and the remaining locations are used to find hotels in the local area.
This repository holds 2 jupyter notebook files as well as image files exported from the first "Weather" notebook file. It also contains a csv of the randomized cities generated.

The following code was devised from: https://www.w3schools.com/python/matplotlib_grid.asp
plt.grid()

https://www.w3schools.com/python/python_functions.asp
def LReg(x,y):

https://stackoverflow.com/questions/34682828/extracting-specific-selected-columns-to-new-dataframe-as-a-copy
hotel_df = filtered_city_data_df[['City','Country', 'Lat', 'Lng','Humidity']].copy()

https://discourse.holoviz.org/t/add-an-extra-field-when-hovering-in-hvplot-scatter/2331
hover_cols=["City","Country","Hotel Name"]

https://www.kdnuggets.com/2019/06/select-rows-columns-pandas.html
 long = hotel_df.loc[index,"Lng"]
 lati = hotel_df.loc[index,"Lat"]
