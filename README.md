# Weather Analysis Dataset

This repository contains a comprehensive weather dataset, suitable for analysis and machine learning projects. The dataset includes hourly weather data recorded over a year, with key meteorological parameters and weather conditions.

## Dataset Overview

The dataset comprises 8,784 entries and 8 columns:

| Column Name         | Description                              | Data Type  |
|---------------------|------------------------------------------|------------|
| `Date/Time`         | Timestamp of the recorded data           | `object`   |
| `Temp_C`            | Temperature in degrees Celsius           | `float64`  |
| `Dew Point Temp_C`  | Dew point temperature in degrees Celsius | `float64`  |
| `Rel Hum_%`         | Relative humidity percentage             | `int64`    |
| `Wind Speed_km/h`   | Wind speed in kilometers per hour        | `int64`    |
| `Visibility_km`     | Visibility in kilometers                 | `float64`  |
| `Press_kPa`         | Atmospheric pressure in kilopascals      | `float64`  |
| `Weather`           | Weather condition description            | `object`   |

## Key Statistics

- **Temperature (`Temp_C`)**: Ranges from -23.3°C to 33°C with an average of 8.8°C.
- **Dew Point Temp (`Dew Point Temp_C`)**: Ranges from -28.5°C to 24.4°C with an average of 2.5°C.
- **Relative Humidity (`Rel Hum_%`)**: Ranges from 18% to 100% with an average of 67.4%.
- **Wind Speed (`Wind Speed_km/h`)**: Ranges from 0 to 83 km/h with an average of 14.9 km/h.
- **Visibility (`Visibility_km`)**: Ranges from 0.2 km to 48.3 km with an average of 27.6 km.
- **Pressure (`Press_kPa`)**: Ranges from 97.52 kPa to 103.65 kPa with an average of 101.05 kPa.
- **Weather Conditions**: Includes 50 unique conditions, e.g., *Mainly Clear*, *Fog*, *Rain*.

## Usage

This dataset can be utilized for:

- Exploratory data analysis (EDA)
- Time series forecasting
- Building predictive models for weather conditions
- Analyzing correlations between meteorological factors

## How to Access the Data

The dataset is available in CSV format:
- File Name: `Weather_Analysis_dataset.csv`
- Number of Rows: 8,784
- Number of Columns: 8

## License

This dataset is provided for educational and research purposes. Please credit this repository if you use the data.

---

Happy analyzing!
