## 📌 Project Overview

This project analyzes global population trends from 1960 to 2025 using World Bank data. The goal is to clean, transform, visualize, and statistically analyze population growth for the top 10 most populous countries. This notebook demonstrates data preprocessing, feature engineering, visualization, and statistical analysis using Python.

## 📂 Dataset

Source: World Bank Population Estimates
Format: CSV

Key Columns
| Column        | Description                                   |
| ------------- | --------------------------------------------- |
| CountryName   | Name of the country                           |
| CountryCode   | ISO country code                              |
| Year          | Year of observation                           |
| Value         | Population count                              |
| IndicatorCode | Metadata indicator (removed in preprocessing) |


## 🧹 Data Preprocessing

The dataset required several cleaning steps:

  - Removed irrelevant columns (IndicatorCode)

  - Filtered only valid country codes (3-character ISO codes)

  - Removed missing values (NaN)

  - Removed aggregated regions (non-country rows)

  - Restructured data for time-series analysis

## 📊 Data Visualization
Population Trends

The project visualizes population trends from 1960–2025 for the 10 most populous countries, including:

  - China
  - India
  - United States
  - Indonesia
  - Pakistan
  - Brazil
  - Nigeria
  - Bangladesh
  - Russia
  - Mexico

Line plots were created to show how population changed over time.

## 📈 Statistical Analysis

For the top 10 countries, the following statistics were computed:

  - Mean population
  - Median population
  - Standard deviation
  - Minimum and maximum population values

This provides insight into long-term population stability and growth patterns.

## 🔍 Key Findings

The top 10 most populous countries consistently dominated global population totals from 1960 onward. Most countries showed steady population growth over time. Some countries (e.g., Russia) showed population stagnation or decline in later years. Population growth rates vary significantly between developing and developed countries.

## 🛠️ Technologies Used

  - Python
  - Python packages (pandas and matplotlib)
  - Jupyter Notebook

## ▶️ How to Run
1. Download the ipynb file in the repository.
2. Open up Jupyter Notebook.
3. Click on "Upload" and choose the downloaded file
4. One the file is in Jupyter Notebook, open up the file and few it!

## 📁 Repository Structure
├── DemmonsDSCI6002A2.ipynb
├── Population-EstimatesCSV.csv
├── README.md

## ⭐ Why This Project Matters

Understanding population trends is critical for healthcare planning, urban development, economics, and public policy.
This analysis demonstrates strong data wrangling, visualization, and statistical reasoning skills relevant to use in future data problems and projects.
