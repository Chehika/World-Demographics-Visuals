# World-Demographics-Visuals

## Overview

This project analyzes and visualizes the age-wise population distribution of the Åland Islands for the year 2018, using publicly available global demographic data. The primary focus is on extracting, cleaning, and visualizing the data through a histogram that reflects the population across different age groups for both sexes.

## Dataset
Source: world_demographics.csv

Filter Criteria:

Country: Åland Islands

Year: 2018

Sex: Both Sexes

Key Columns Used: Age, Value, Country or Area, Year, Sex

 ## Process
Data Loading: Load the CSV file into a pandas DataFrame.

Filtering: Extract data only for the Åland Islands for the year 2018.

Data Cleaning: Convert Age and Value columns to numeric types, handling non-numeric entries gracefully.

Visualization: Create a bar plot using matplotlib to visualize age distribution.

## Visualization
The histogram represents the number of individuals in each age group in the Åland Islands for 2018. It offers a quick visual insight into the population pyramid and demographic trends.

## Conclusion
This project demonstrates how demographic data can be filtered, cleaned, and visualized using Python. It provides a simple but powerful example of real-world data analysis using pandas and matplotlib.

