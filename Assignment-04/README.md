# Climate Data Analysis for a Research Center

## Overview
As a data scientist, you will analyze daily temperature and humidity data from 500 locations over one year to identify trends and seasonal patterns.

## Tasks

1. **Initialize Data**: Generate `temperature_data` (Celsius, -10 to 40°C) and `humidity_data` (0 to 100%) arrays.
2. **Check Missing Data**: Randomly set 5% of values to null and report the total missing entries.
3. **Convert Temperature**: Convert Celsius to Fahrenheit and calculate a "feels like" index, capping values at 80.
4. **Analyze January**: Extract January temperatures and calculate the average for all locations.
5. **Identify Extremes**: Replace temperatures >35°C with nulls and count the number of nulls per location.
6. **Quarterly Averages**: Reshape data into four quarters and calculate average temperatures for each location.
7. **Humidity Levels**: Classify humidity as "Dry" (<30%) or "Humid" (>70%) and count days for each category.
8. **Pressure Trend**: Adjust temperatures based on daily atmospheric pressure variations.


