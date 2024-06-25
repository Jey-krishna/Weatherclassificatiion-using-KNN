# Weather Classification

## Overview
The goal of this project is to classify weather conditions based on various features using machine learning algorithms. The notebook includes data preprocessing, feature analysis, model training, and evaluation.

## Dataset
* Temperature (numeric): The temperature in degrees Celsius, ranging from extreme cold to extreme heat.
* Humidity (numeric): The humidity percentage, including values above 100% to introduce outliers.
* Wind Speed (numeric): The wind speed in kilometers per hour, with a range including unrealistically high values.
* Precipitation (%) (numeric): The precipitation percentage, including outlier values.
* Cloud Cover (categorical): The cloud cover description.
* Atmospheric Pressure (numeric): The atmospheric pressure in hPa, covering a wide range.
* UV Index (numeric): The UV index, indicating the strength of ultraviolet radiation.
* Season (categorical): The season during which the data was recorded.
* Visibility (km) (numeric): The visibility in kilometers, including very low or very high values.
* Location (categorical): The type of location where the data was recorded.
* Weather Type (categorical): The target variable for classification, indicating the weather type.

## Steps involved in the  classification of weather
1. **Data Loading and Preprocessing:** Loading the dataset and performing preprocessing steps such as handling missing values and encoding categorical variables.
2. **Exploratory Data Analysis (EDA):** Analyzing the dataset to understand the distribution of features and target variables.
3. **Feature Importance Analysis:** Identifying important features using Random Forest feature importance.
4. **Model Training and Evaluation:**  Training machine learning models and evaluating their performance using metrics such as accuracy and classification report.
