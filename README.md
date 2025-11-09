# DSA5208 Project 2: Weather Data Analysis and Temperature Prediction

## Overview

This project analyzes NOAA Global Hourly weather data for 2024 to predict temperature (TMP_VALUE) using various meteorological features. The analysis includes data preprocessing, correlation studies, and building multiple regression models to forecast temperature based on factors like wind, visibility, ceiling height, dew point, and sea-level pressure.

## Project Structure

- `correlation_analysis.ipynb`: Exploratory data analysis focusing on correlations between weather variables and temperature.
- `data_preprocessing_final.ipynb`: Data cleaning, parsing, and preparation of raw NOAA data.
- `model_building_final.ipynb`: Implementation and evaluation of regression models (Linear Regression, Decision Trees, Random Forest, Gradient Boosted Trees).
- `requirements.txt`: Python dependencies required to run the notebooks.
- `2024_Dataset/`: Raw weather data files (downloaded from NOAA). This is created by data downloading steps below.
- `2024_cleaned_data/`: Directory to store the cleaned data after preprocessing. This is created by running `data_preprocessing_final.ipynb`.
- `models/`: Directory that stores all the trained models, with the best hyperparameters. 

## Environment and Data Download
- You may set a virtual environment and install libraries based on the `requirements.txt`.
- You may download the dataset from the source with the following steps:
   ```
   bash
   mkdir 2024_Dataset
   wget https://www.ncei.noaa.gov/data/global-hourly/archive/csv/2024.tar.gz
   tar xf 2024.tar.gz -C 2024_Dataset/
   ```





