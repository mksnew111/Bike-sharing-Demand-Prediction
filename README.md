# Bike-sharing-Demand-Prediction
# Project Summary:- 
A bike rental or bike hire business offers bicycles for short durations, typically a few hours, catering primarily to individuals without personal vehicle access, notably travelers and tourists, akin to car rental services. These rental shops provide bikes for daily, weekly, and hourly periods. Presently, rental bikes are being introduced in numerous urban areas to improve mobility convenience. Ensuring timely availability and accessibility of rental bikes is crucial to minimize wait times.

# Problem Statement: - 
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Dataset Description: - 

Date: Date of Rented Bike
Rented Bike count: Number of total rentals
Hour: Hours of the day
Temperature(°C): Weather Temperature in °C
Humidity(%): Humidity of the day in %
Wind speed (m/s): Wind speed in m/s
Visibility (10m): Atmospherical Visibility within 10 𝑚 range
Dew point temperature(°C): Dew Point Temperature - T in °C
Solar Radiation (MJ/m2): Indicate light and energy that comes from the sun in MJ/m2
Rainfall(mm): Rain fall in mm
Snowfall (cm): Snow fall in cm
Seasons: Autumn, Spring, Summer, Winter
Holiday: Whether the day is considered a holiday
Day: Whether the day is neither a weekend nor holiday

In this dataset, we have 14 features and 8760 observations.
There are 10 Numeric features and 4 categorical features.
Columns: Rented Bike Count, Hour, Humidity and visibility are of int64 numeric data types.
columns: Temperature, Wind speed, Dew point temperature, Solar Radiation, Rainfall, Snowfall are of float64 numeric data types.
Columns: Date, Seasons, Holiday and Functioning Day are object data types.
No Duplicate rows are present in the dataset.
Not any Null values present in any Columns.

# conclusion:-
# EDA: Insights
1. On No holiday, i.e., working days, a higher number of bikes are rented.

2. During the summer, bike rentals reached their peak, with the highest number of bikes being rented. Conversely, the winter season experienced the lowest number of bike rentals.
    
3.The highest number of bike rentals occurs within the temperature range of 10 to 30 degrees Celsius. Similarly, the majority of bikes 
are rented when the humidity level falls between 30 and 70 percentage.

4.The peak demand for bikes is observed during the evening hours from 4 PM to 8 PM.

5.customer preferred higher visibility.

# ML: Insights
It's evident that the Random Forest model is surpassing other models in terms of metrics. Additionally, the overall accuracy of the model has increased from 0.47 to 0.80

# Challenges Faced:
1. Handling Outliers.
2. Removing Multicollinearity.
