# Weather-Classification-using-Decision-Tree
In this notebook I will predict weather using Decision Tree.

Each row, or sample, consists of the following variables:

number: unique number for each row
air_pressure_9am: air pressure averaged over a period from 8:55am to 9:04am (Unit: hectopascals)
air_temp_9am: air temperature averaged over a period from 8:55am to 9:04am (Unit: degrees Fahrenheit)
air_wind_direction_9am: wind direction averaged over a period from 8:55am to 9:04am (Unit: degrees, with 0 means coming from the North, and increasing clockwise)
air_wind_speed_9am: wind speed averaged over a period from 8:55am to 9:04am (Unit: miles per hour)
max_wind_direction_9am: wind gust direction averaged over a period from 8:55am to 9:10am (Unit: degrees, with 0 being North and increasing clockwise)
max_wind_speed_9am: wind gust speed averaged over a period from 8:55am to 9:04am (Unit: miles per hour)
rain_accumulation_9am: amount of rain accumulated in the 24 hours prior to 9am (Unit: millimeters)
rain_duration_9am: amount of time rain was recorded in the 24 hours prior to 9am (Unit: seconds)
relative_humidity_9am: relative humidity averaged over a period from 8:55am to 9:04am (Unit: percent)
relative_humidity_3pm: relative humidity averaged over a period from 2:55pm to 3:04pm (Unit: percent )

In this dataset we will binarize the relative_humidity_3pm to 0 or 1 and then predict whether the weather is humid or not using decision tree algorithm.

I have got an accuracy score **0.81534090909090906**.
