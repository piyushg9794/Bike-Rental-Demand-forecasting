# Bike-Rental-Demand-forecasting
Machine learning model using scikit learn (python)

Using historical usage patterns and weather data, predict bike rental demand (number of bike users (‘cnt’)) on hourly basis.

Using the provided data set to predict the bike demand (bike users count - 'cnt') using various best possible models (ML algorithms). Also, report the model that performs best, fine-tune the same model using one of the model fine-tuning techniques, and report the best possible combination of hyperparameters for the selected model. Lastly, use the selected model to make final predictions and compare the predicted values with the actual values.

## Dataset description-

1) instant: record index

2) dteday : date

3) season: season (1: springer, 2: summer, 3: fall, 4: winter)

4) yr: year (0: 2011, 1:2012)

5) mnth: month (1 to 12)

6) hr: hour (0 to 23)

7) holiday: whether the day is a holiday or not

8) weekday: day of the week

9) workingday: if day is neither weekend nor holiday is 1, otherwise is 0.

10) weathersit:

  1: Clear, Few clouds, Partly cloudy, Partly cloudy

  2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

  3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

  4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

11) temp: Normalized temperature in Celsius. The values are derived via (tt_min)/(t_maxt_min), t_min=*8, t_max=+39 (only in hourly scale)

12) atemp: Normalized feeling temperature in Celsius. The values are derived via (tt_min)/(t_maxt_min), t_min=*16, t_max=+50 (only in hourly scale)

13) hum: Normalized humidity. The values are divided to 100 (max)

14) windspeed: Normalized wind speed. The values are divided to 67 (max)

15) casual: count of casual users

16) registered: count of registered users

17) cnt: count of total rental bikes including both casual and registered users

## Main Steps Involved

1- We will be following the below steps to solve this problem

2- Importing the libraries

3- Using some pre-defined utility functions

4- Loading the data

5- Cleaning the data

6- Dividing the dataset into training and test dataset

7- using train_test_split in the ratio 70:30

8- Training several models and analyzing their performance to select a model

9- Fine-tuning the model by finding the best hyper-parameters and features

10- Evaluating selected model using test dataset


