# NYC Taxi Trip EDA

## Overview
This project performs **Exploratory Data Analysis (EDA)** on NYC Taxi trip data. It involves data loading, cleaning, visualization, and geospatial analysis to extract insights about trip patterns, revenue trends, and taxi zone distribution.

## Features
- **Data Preprocessing**: Cleaning and handling missing values.
- **Descriptive Statistics**: Analyzing trip duration, fare distribution, and passenger count.
- **Time-based Analysis**: Understanding hourly, daily, and monthly trip trends.
- **Revenue Trends**: Identifying seasonal revenue patterns.
- **Geospatial Analysis**: Mapping trips per zone using NYC Taxi Zones shapefile.

## Project Structure
NYC_Taxi_EDA/ │-- data/ # Dataset and shapefiles (not included in repo) │-- notebooks/ # Jupyter Notebooks for analysis │-- scripts/ # Python scripts for EDA and visualization │-- results/ # Output plots and summary reports │-- README.md # Project documentation │-- requirements.txt # Dependencies │-- eda_analysis.py # Main EDA script

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/NYC_Taxi_EDA.git

2. Navigate to the project folder:
cd NYC_Taxi_EDA

3. Create a virtual environment (optional but recommended):
python -m venv venv source venv/bin/activate # On Windows use: venv\Scripts\activate
