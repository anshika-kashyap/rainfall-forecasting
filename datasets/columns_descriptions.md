# Columns Descriptions

The descriptions of the following columns are based on the raw train dataset:

- id: Unique identifier for each record.
- day: Day of the year, ranging from 1 to 365.
- pressure: Barometric pressure measured in hectopascals.
- maxtemp: Highest temperature recorded on a given day in degrees Celsius.
- temparature: Average temperature recorded on a given day in degrees Celsius.
- mintemp: Lowest temperature recorded on a given day in degrees Celsius.
- dewpoint: Temperature at which air becomes saturated with moisture, leading to dew formation, in degrees Celsius.
- humidity: Relative humidity percentage.
- cloud: Percentage of the sky covered by clouds on a given day.
- sunshine: Total hours of sunshine recorded on a given day.
- winddirection: Direction from which the wind is blowing in degrees.
- windspeed: Wind speed measured in kilometers per hour.
- rainfall: Binary target variable indicating rainfall occurrence (1 for rain, 0 for no rain).

# Note

All columns are present in both the datasets except the 'rainfall' column is not present in the 'test' dataset.
