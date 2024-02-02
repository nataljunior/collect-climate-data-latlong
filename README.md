# Weather Data Analysis

## Overview

This repository contains code for collecting and analyzing daily weather data from the NASA Power API. The provided Python scripts utilize the Pandas library for data manipulation and analysis.

## Code Structure

### Data Collection
- The `collect_data` function retrieves daily weather data such as precipitation and temperature from the NASA Power API for a given latitude and longitude.

### Data Transformation
- The collected data is transformed into a structured DataFrame using Pandas.
- The 'parameter' column is pivoted into separate columns for easier analysis.

### Data Analysis
- The script calculates various statistics and features using rolling windows and group-by operations, including rolling sums and averages for precipitation and temperature.
- Monthly and annual averages for temperature are computed, along with yearly minimum and maximum temperatures.
- The annual sum of precipitation is also calculated.
