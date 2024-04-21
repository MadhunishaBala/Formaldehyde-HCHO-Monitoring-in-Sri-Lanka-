# Formaldehyde-HCHO-Monitoring-in-Sri-Lanka-

An analysis was carried out to assess air quality in Sri Lanka using formaldehyde (HCHO) data collected from Sentinel-5p satellite observations across seven cities spanning from 2019 to 2023. The analysis involved preprocessing the data, visualizing trends, and employing machine learning techniques to understand HCHO concentration levels and their correlation with factors such as population density, precipitation, and temperature. 

## Data Cleaning
- Load the csv files
- Seperate it into seven cities
- Convert date to datetime format
- Convert Negative values to NaN
- Interpolate the null values
- Remove outliers
- Boxplot & Histogram Visualization

## Spatio- Temporal Analysis
- Determining long-term trends using moving averages
- Detrmining trends in HCHO reading for changes in population
- Detrmining trends in HCHO reading during COVID19 analysis
- Determining trends in HCHO reading for changes in Precipitation
- Determining trends in HCHO reading for changes in Total Average Temperature

## Feature Engineering
- Label encoding the location
- Date colums are encoded using toordinal()
- Scaling the date feature

## Machine Learning
- Train model using LSTM
- Calculate the Mean Squared Error
- Calculate the Mean Absolute Error
- Calculate the Root Mean Squared Error and Median Absolute Error

## Dashboards

![Screenshot 2024-04-21 151652](https://github.com/MadhunishaBala/Formaldehyde-HCHO-Monitoring-in-Sri-Lanka-/assets/127708789/2385e3a8-5db9-498d-8129-f7f5c1453642)


![Screenshot 2024-04-21 151824](https://github.com/MadhunishaBala/Formaldehyde-HCHO-Monitoring-in-Sri-Lanka-/assets/127708789/2d7ccc18-aefd-406a-9575-9148bdc4a574)


![Screenshot 2024-04-21 151942](https://github.com/MadhunishaBala/Formaldehyde-HCHO-Monitoring-in-Sri-Lanka-/assets/127708789/ca1abf40-4b0f-4659-ab69-f7f59a4cc06e)


![Screenshot 2024-04-21 152024](https://github.com/MadhunishaBala/Formaldehyde-HCHO-Monitoring-in-Sri-Lanka-/assets/127708789/657a1e82-4c4d-483c-ba14-49dea5a4d214)



