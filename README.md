# London Bike Ride Analysis

## Introduction
This project analyzes London bike sharing data to uncover usage patterns and the impact of weather conditions on bike rides. Using Python and Tableau, dynamic visualizations provide insights into bike usage trends, helping to optimize bike sharing services.

## Data Source
The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset), includes detailed records of bike rides in London. Key attributes include timestamps, temperature, humidity, wind speed, and weather conditions. This comprehensive dataset allows for in-depth analysis of temporal and environmental impacts on bike ride frequency.

## Technologies Used
- **Python**: Used for data manipulation and cleaning with the Pandas library.
- **Tableau**: Employed to create dynamic and interactive visualizations.
- **Kaggle API**: For programmatically downloading the dataset.

## Files in the Repository
This repository contains several key files that contribute to the project's functionality:
- **LondonBikeRideAnalysis.twbx**: The Tableau dashboard file showcasing the visual analysis of the London bike sharing data.
- **London_Bikes_Data.ipynb**: A Jupyter notebook containing the Python code used for data cleaning and preparation.
- **london_bikes_cleaned.xlsx**: The cleaned Excel file output from the Python script, ready for visualization.
- **london_merged.csv**: The original dataset downloaded from Kaggle, used as the basis for the analysis.

## Features of the Dashboard
The Tableau dashboard includes several interactive features:
- **Total Bike Rides**: Visualizes the total number of rides.
- **Moving Average Chart**: Shows trends over time with adjustable parameters.
- **Temperature vs. Wind Speed Heat Map**: Analyzes environmental factors affecting bike usage.
- **Interactive Tooltips**: Provide additional data on bike rides by weather and hour.

View the interactive dashboard [here](https://public.tableau.com/views/LondonBikeRideAnalysis_17389822968590/Dashboard).
