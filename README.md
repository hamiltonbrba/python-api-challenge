# python-api-challenge
Module 6 Challenge - Python Api


Got it! Here’s an updated README without mentioning asynchronous requests and focusing on the actual steps you took:

### README

# Weather and Vacation Analysis

## Overview

This project involves two main parts:
1. **WeatherPy**: Visualizing the weather of over 500 cities of varying distances from the equator.
2. **VacationPy**: Planning future vacations based on ideal weather conditions and mapping out the locations of nearby hotels.

## Part 1: WeatherPy

### Objective

Create a Python script to visualize the weather of over 500 cities across the world. The data is analyzed to identify relationships between latitude and various weather parameters.

### Steps

1. **Generate Random Geographic Coordinates**:
   - Used the `numpy` library to generate random latitude and longitude combinations.
   
2. **Find Nearest Cities**:
   - Utilized the `citipy` library to identify the nearest city for each set of geographic coordinates.
   
3. **Retrieve Weather Data**:
   - Employed the OpenWeatherMap API to gather current weather data for each city.
   
4. **Visualize Relationships**:
   - Created scatter plots to visualize relationships between latitude and temperature, humidity, cloudiness, and wind speed.
   - Performed linear regression analysis to further explore these relationships.

### Usage

1. **Dependencies**:
   - Python libraries: `matplotlib`, `pandas`, `numpy`, `requests`, `time`, `scipy`, `citipy`
   
2. **Running the Script**:
   - Ensure you have an API key from OpenWeatherMap.
   - Update the `weather_api_key` variable in the script with your API key.
   - Run the Jupyter notebook `WeatherPy.ipynb` to generate plots and analysis.

### Code Sources

- The section of code for generating random latitude and longitude coordinates was based on numpy's uniform distribution function examples.
- The usage of the `citipy` library for finding the nearest city was adapted from the library's documentation.

