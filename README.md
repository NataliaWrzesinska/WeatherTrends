# WeatherTrends

# Weather Trends Analysis in Poland (2014-2023)

## Project Overview
This project focuses on analyzing weather trends in Poland from 2014 to 2023. It involves gathering, processing, and analyzing weather data such as temperature and precipitation patterns to identify long-term trends and predict future climate conditions. The project utilizes machine learning techniques, including Random Forest models, for climate prediction, and provides detailed visualizations of the results.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Data Preparation](#data-preparation)
- [How to Run](#how-to-run)
- [Data Analysis](#data-analysis)
- [Climate Prediction](#climate-prediction)
- [Data Security](#data-security)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Contributing](#contributing)

## Features
- **Automated Data Collection:** Fetches weather data from NOAA or similar sources.
- **Data Cleaning and Processing:** Fills missing values, removes duplicates, and performs initial validation.
- **Trend Analysis:** Analyzes annual and seasonal trends for temperature and precipitation.
- **Extreme Values Analysis:** Identifies extreme weather conditions (maximum/minimum temperatures).
- **Machine Learning Predictions:** Uses Random Forest models to predict future temperatures (e.g., for 2024).
- **Data Visualization:** Provides detailed charts and graphs for easy interpretation of trends.
- **Database Storage:** Stores data securely in SQLite databases for easy access and management.

## System Requirements
- **Python:** 3.7 or newer

### Required Python Libraries:
- pandas
- numpy
- matplotlib
- scikit-learn
- sqlite3

## Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/weather-trends-analysis.git
cd weather-trends-analysis
