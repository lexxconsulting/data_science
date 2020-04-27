Summary

This experiment aims to create a predictive model for
estimate the demand for bicycle rentals.

Description:
This experiment aims to demonstrate the process of building a model
regression to forecast demand for bicycle rentals. We will use a
data set to build and train our model.

Data:
The “Bike Rental UCI” data set will be used to build and train the
model in this experiment. This dataset is based on real company data
Capital Bikeshare, which operates bicycle rentals in Washington DC,
In the USA.
The dataset contains 17,379 observations and 17 variables, representing the
number of bikes rented within specific hours of the day, in the
2011 and 2012. Climatic conditions (such as temperature, humidity and speed of
wind) were included in the dataset and the dates were categorized as holidays and
days of the week.

Dataset: https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

objective
The objective will be to predict the value of the variable cnt (count) that represents the
number of bikes rented within a specific hour and whose range is
from 1 to 977

Attribute Information:
Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv

- instant: record index
- dteday : date
- season : season (1:winter, 2:spring, 3:summer, 4:fall)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : weather day is holiday or not (extracted from [Web Link])
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
+ weathersit :
- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered
