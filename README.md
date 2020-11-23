# Weather Trends

This project was the introduction to writing HTML, CSS, and Boostrap code and uses the information from [Weather Trends and API Calls](https://github.com/dan-edie/Weather-Trends-and-API-Calls), a project that used data to look at weather patterns in the Northern and Southern hemispheres. From that project, only the most relevant data is presented.

A quick overview of the method and results:
* Two API calls were made. The first used a random choice of latitiude and longitude to find the nearest population center with Citipi. This city was then fed into another API call to pull specific weather information.
* There is a correlation with maximum temperatures as you approach the equator, which is expected given the amount of direct sunlight year-long encountered as you approach the equator.
* There are fewer data points in the Southern Hempisphere, which may be accounted for by fewer API calls from cities in the Southern Hemisphere, which in turn could be due to less landmass in the Southern Hemisphere (due to the larger amounts of ocean water in the Southern Hemisphere).
* Other plots created, such as humidity, cloud cover, and wind speed, are not affected by the location of the data pulled.
* Using Google, the cities pulled were plotted with a heatmap based on specified vacation requirements (temperature between 70 and 80 degrees F, zero average cloud cover, and average wind speeds of less than 10 mph), and a list of five cities and hotels were plotted.
