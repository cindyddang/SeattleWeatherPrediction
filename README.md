# SeattleWeatherPrediction

This project focuses on predicting the next day’s weather category (drizzle, rain, snow, fog, or sun) in Seattle using historical weather data. Seattle is a city known for its variable and often unpredictable climate, with frequent rain and mild temperatures, so we analyze weather patterns over the preceding seven days before prediction with different models.

## Dataset

The dataset used in this project is the [Seattle Weather Prediction Dataset](https://www.kaggle.com/datasets/petalme/seattle-weather-prediction-dataset). It contains daily weather observations, including:

Precipitation: Total daily rainfall in millimeters.

Temperature (Max/Min): The highest and lowest temperatures of the day in Celsius.

Wind Speed: Average daily wind speed in meters per second.

Weather Category: A label describing the overall weather (drizzle, rain, snow, fog, sun).

## Models implemented

- Random Forest (rf_seattles.py)
- Support Vector Machine (SVM_seattles.py)
- Gradient Boosting (GBoosting_seattles.py)
- Long Short-Term Memory (LSTM_seattles.py)
