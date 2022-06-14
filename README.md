# Where is your ideal vacation, based on weather conditions?

## Part I - Tracking Major Weather Conditions around the World

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Pulled data from the Open Weapther Maps API.

Created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.

Conducted a linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, explained what the linear regression is modeling. 

![image](https://user-images.githubusercontent.com/90559756/163395161-9e172317-3717-4250-bc3a-5532e2462f6d.png)


### Part II - Planning a Vacation

Used jupyter-gmaps and the Google Places API to create a heat map that displays the humidity for every city from Part I.

 Narrowed down the DataFrame to find locations with the following ideal weather conditions:
 
  * A maximum temperature between 50 and 70 degrees Fahrenheit.

  * Wind speed less than 10 mph.

  * Humidity between 20 and 40 percent.

  ![image](https://user-images.githubusercontent.com/90559756/163396375-662a58dd-b003-4c23-8549-449d636d6795.png)

![image](https://user-images.githubusercontent.com/90559756/163396551-441a60bc-a273-4fa1-a3c2-4707623261ca.png)

Used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.

Plotted the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

![image](https://user-images.githubusercontent.com/90559756/163396578-208a2eff-7ff7-47bd-ad99-af91b191df54.png)

 
