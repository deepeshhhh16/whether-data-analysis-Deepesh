# Weather Data Analysis

## Overview
This project provides an analysis of weather data, including temperature, rainfall, and humidity over a period of time. The script generates summary statistics, visualizes trends, and examines correlations between meteorological factors.

## Features
- Reads weather data from a CSV file.
- Converts the date column to a datetime format.
- Generates summary statistics for temperature, rainfall, and humidity.
- Plots time series trends for temperature, rainfall, and humidity.
- Computes and visualizes the correlation matrix between variables.

## Requirements
The script requires the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using:
```sh
pip install pandas matplotlib seaborn
```

## Usage
1. Ensure your weather data is in a CSV file (e.g., `weather_data.csv`).
2. Update the file path in the script if necessary.
3. Run the script using:
```sh
python weather_analysis.py
```
4. The script will generate summary statistics and display graphical trends.

## Output
- Summary statistics printed in the console.
- Line plots for temperature, rainfall, and humidity trends.
- A heatmap showing correlations between weather parameters.

## Author
This script was developed for analyzing weather data and identifying key patterns.

## License
This project is open-source and available for modification and use under the MIT License.

