# Weather Data Analysis

A data science project for exploring and modeling weather data with multiple meteorological features, designed for predictive analytics and insights.

## 📄 Dataset Overview

The dataset contains daily weather observations from multiple locations, with the following columns:
- **Date**: Observation date
- **Location**: Weather station location
- **MinTemp**: Minimum temperature (°C)
- **MaxTemp**: Maximum temperature (°C)
- **Rainfall**: Amount of rainfall (mm)
- **Evaporation**: Evaporation (mm)
- **Sunshine**: Daily sunshine (hours)
- **WindGustDir**: Wind gust direction
- **WindGustSpeed**: Wind gust speed (km/h)
- **WindDir9am/3pm**: Wind direction at 9am/3pm
- **WindSpeed9am/3pm**: Wind speed at 9am/3pm (km/h)
- **Humidity9am/3pm**: Humidity at 9am/3pm (%)
- **Pressure9am/3pm**: Atmospheric pressure at 9am/3pm (hPa)
- **Cloud9am/3pm**: Cloud cover at 9am/3pm (oktas)
- **Temp9am/3pm**: Temperature at 9am/3pm (°C)
- **RainToday**: Whether it rained today (Yes/No)
- **RainTomorrow**: Target variable – whether it will rain tomorrow (Yes/No)

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn