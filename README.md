# surfs_up:
### unit 9

## Overview of the analysis:
Using Python, Pandas functions and methods, and SQLAlchemy, we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. We then converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics. We also saved the images to our resources folder, which I am going to add here for more explanation. Our challenge was that an investor wanted to learn more about the weather before deciding to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern was the precipitation in the area forcing the shop to close too often. To analyze Hawaii's weather data, we used SQLAlchemy to query the SQLite database.

## Results:

Image of June Statistics for Temperature and Precipitation:

![June prcp stats](https://github.com/KJoshi111/surfs_up/blob/main/Resources/June%20temp-prcp%20stats.png)

Image of December Statistics for Temprature and Precipitation:

![Dec prcp stats](https://github.com/KJoshi111/surfs_up/blob/main/Resources/Dec%20temp-prcp%20stats.png)

### Analysis of the Results:
The mean temperature for June, 75°F, is higher than the mean temperature for December, 71°F. However, the opposite is true for precipitation. December had the higher mean precipitation, 0.22 inches, while June's mean precipitation was 0.14 inches.
Here are the Images of the Graphs:

![temps in June](https://github.com/KJoshi111/surfs_up/blob/main/Resources/Temps%20in%20June.png)

![temps in Dec](https://github.com/KJoshi111/surfs_up/blob/main/Resources/Temps%20in%20Dec.png)




## Summary:
Our client's main concern was getting rain too frequently. Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close. The temperature data is not strongly skewed for either month. The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation. The data supports that we can open a Surf and Ice Cream shop year-round and keep it profitable as weather is not an obstacle
