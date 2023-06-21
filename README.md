# Bike Sharing Demand Prediction 

This repository contains code for predicting bike sharing demand using AutoGluon, as part of an Udacity project. The project aims to build a machine learning model that accurately predicts the number of bikes rented in a bike-sharing program based on various features such as weather conditions, time of day, and other relevant factors.

## Dataset Source

The dataset used for this project was sourced from Kaggle. It provides historical hourly rental data for a bike-sharing program, along with corresponding weather and seasonal information. The dataset consists of the following columns:

- `datetime`: Timestamp of the observation
- `season`: Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter)
- `holiday`: Whether the day is a holiday or not (1 = yes, 0 = no)
- `workingday`: Whether the day is a working day or not (1 = yes, 0 = no)
- `weather`: Weather condition (1 = clear, 2 = mist, 3 = light rain/snow, 4 = heavy rain/snow)
- `temp`: Normalized temperature in Celsius
- `atemp`: Normalized "feels-like" temperature in Celsius
- `humidity`: Normalized humidity level
- `windspeed`: Normalized wind speed
- `casual`: Number of non-registered users (casual rentals)
- `registered`: Number of registered users (registered rentals)
- `count`: Total number of bikes rented (casual + registered)

Please note that the dataset used in this project is available for download from Kaggle. Ensure that you have the necessary permissions to access and use the dataset for your own purposes.

## AutoGluon

AutoGluon is an open-source library developed by Amazon that provides a high-level interface for automating machine learning tasks. It simplifies the process of training and tuning machine learning models by automatically searching for the best model architecture and hyperparameters. AutoGluon supports a wide range of machine learning tasks, including regression, classification, and time series forecasting.


## Contact Information

If you have any questions or need further information, please feel free to reach out to the project owner at patwarinavin9@gmail.com.

Happy coding!
