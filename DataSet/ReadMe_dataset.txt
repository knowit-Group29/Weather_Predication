
README for Pune Weather Dataset
===============================

Dataset Overview
----------------
The Pune Weather dataset consists of 45,503 entries and 23 columns, containing hourly weather observations from Pune, India. This dataset includes various weather parameters, such as temperature, humidity, wind speed, and more, recorded over time.

File Name:
----------
- pune.csv

Columns Description:
--------------------
1. date_time: The date and time of the observation (format: YYYY-MM-DD HH:MM:SS).
2. maxtempC: Maximum temperature recorded in Celsius.
3. mintempC: Minimum temperature recorded in Celsius.
4. sunHour: Number of sunshine hours.
5. uvIndex: UV Index value.
6. moon_illumination: Percentage of the moon illuminated.
7. moonrise: Time of moonrise.
8. moonset: Time of moonset.
9. sunrise: Time of sunrise.
10. sunset: Time of sunset.
11. DewPointC: Dew point temperature in Celsius.
12. FeelsLikeC: Temperature as felt by humans in Celsius.
13. HeatIndexC: Heat index in Celsius.
14. WindChillC: Wind chill in Celsius.
15. WindGustKmph: Wind gust speed in kilometers per hour.
16. cloudcover: Cloud cover percentage.
17. humidity: Humidity percentage.
18. precipMM: Precipitation in millimeters.
19. pressure: Atmospheric pressure in hPa.
20. tempC: Actual temperature in Celsius.
21. visibility: Visibility distance in kilometers.
22. winddirDegree: Wind direction in degrees.
23. windspeedKmph: Wind speed in kilometers per hour.

Missing Values:
---------------
Some columns have missing values, such as maxtempC, mintempC, sunHour, etc. These need to be handled appropriately during data processing.

Usage:
------
This dataset can be used for various weather-related analyses, including but not limited to:
- Time series forecasting.
- Climate pattern analysis.
- Correlation studies between different weather parameters.
- Data visualization projects.

How to Load the Dataset:
------------------------
You can load the dataset using Python's pandas library:

```python
import pandas as pd

# Load the dataset
file_path = 'path/to/pune.csv'
data = pd.read_csv(file_path)
```

Data Cleaning:
--------------
- Handle missing values through imputation or removal.
- Convert date_time to datetime format for time-based analyses.

Sample Record:
--------------
```
date_time          : 2017-01-01 01:00:00
maxtempC           : 31.0
mintempC           : 17.0
sunHour            : 11.0
uvIndex            : 6.0
moon_illumination  : 20.0
moonrise           : 09:15 AM
moonset            : 08:58 PM
sunrise            : 07:07 AM
sunset             : 06:09 PM
DewPointC          : 18.0
FeelsLikeC         : 18
HeatIndexC         : 18
WindChillC         : 18.0
WindGustKmph       : 5.0
cloudcover         : 1
humidity           : 63
precipMM           : 0.0
pressure           : 1014.0
tempC              : 18
visibility         : 10
winddirDegree      : 82
windspeedKmph      : 2
```

License:
--------
Please make sure to adhere to any licensing requirements that apply to the data source.
