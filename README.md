# Motor Vehicle Collisions Data Analysis
==============================================================

## Introduction
This project involves the analysis of Motor Vehicle Collisions data from May 1, 2017, to April 30, 2019, focusing on the vehicle makes Ford, Honda, KW, and Volk. The aim is to draw insights into accident trends and patterns involving these specific vehicles.

## Getting Started
- Import necessary libraries: Pandas, Numpy, Matplotlib.
- Load Motor Vehicle Collisions data using Pandas.
- Filter data based on the specified date range and selected vehicle makes (Hond, Ford, Volk, KW).
- Prepare the data for analysis by handling multiple vehicle names and ensuring consistency.

## Usage
=============================================================
### Data Preprocessing:

- Filter data based on the date range and selected vehicle makes.
- Standardize vehicle make names for consistency.
- Create a smaller dataset with relevant columns (CRASH_DATE, VEHICLE_MAKE).

### Compression
The pre-processed dataset has been compressed to reduce file size. You can find the compressed dataset as dataset.zip. Follow these steps to use the compressed dataset:

1. Download the compressed dataset file i.e - dataset.zip.
2. Extract the contents of the compressed file to obtain the "vehicle_types_analysis.csv" file.

### Analysis 1 - Number of Accidents by Vehicle Make:

- Group data by year and vehicle make.
- Plot a bar graph to visualize the number of accidents for each vehicle make per year.
- Analyze the results to identify vehicles with the highest and lowest accident counts.

### Analysis 2 - Monthly Accidents by Vehicle Make:

- Create a smaller dataset with CRASH_DATE and VEHICLE_MAKE columns.
- Group data by vehicle make and month.
- Plot a line graph to visualize monthly accidents for each vehicle make.
- Analyze the results to identify any specific months or seasons that are more accident-prone.

### Analysis 3 - Percentage of Crashes by Vehicle Type:

- Preprocess the vehicle type column to identify the 10 most accident-prone types.
- Group data by vehicle type and calculate the percentage of accidents for each type.
- Plot a pie chart to visualize the distribution of accidents by vehicle type.
- Analyze the results to identify the most and least accident-prone vehicle types.

## Contributing
Feel free to contribute by providing feedback, suggesting improvements, or reporting issues. Follow the guidelines in the repository.
