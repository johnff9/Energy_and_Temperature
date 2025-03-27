# Global Temperature Analysis

## Overview
This project analyzes global temperature changes over the years using data visualization techniques in Python. The dataset contains historical temperature variations categorized by month and year, providing insights into climate trends. As well as the energy consumption from each country and how renewable energy is being produced as well as how much is being produced.

## Features
- **Data Cleaning & Transformation**: Prepares the dataset for visualization by reshaping it from wide to long format.
- **Exploratory Data Analysis (EDA)**: Summarizes data trends and distributions.
- **Visualization with Seaborn & Matplotlib**: Creates insightful graphs to depict temperature changes over time.
- **Aggregation & Grouping**: Allows analysis of temperature changes by month and year.

## File Structure
- `data/` - Raw dataset folder
- `Data_analysis.ipynb` - Jupyter notebook for analysis
- `README.md` - Project documentation
- `requirments.yml` - Anaconda enviroment setup


### Climate Analysis
- Annual temperature trends with confidence bands
- Meteorological year analysis
- Standard deviation visualization

### Energy Analysis
- World energy consumption patterns (1985-2022)
- Geospatial renewable energy mapping
- 20-year energy production mix evolution
- Renewable vs fossil fuel generation trends

### Statistical Insights
- GDP-renewable energy regression analysis
- Outlier detection in energy adoption
- IQR-based data cleaning
- Pearson correlation coefficients

📂 Data Sources
- Climate Data:
    - Environment_Temperature_change_E_All_Data_NOFLAG.csv
    - FAOSTAT-derived temperature records

- Energy Data:
    - World Energy Consumption.csv
    - modern-renewable-prod.csv
    - renewable-share-energy.csv

- Geospatial Data:
    - Natural Earth 110m countries dataset
    - ISO country codes mapping
# Temperature Change Visualization
Section [2]: Global Annual Temperature Change

# Geospatial Energy Mapping
Section [4]: 2022 Renewable Energy World Map

# Energy Production Evolution
Section [6]: 20-Year Energy Mix Comparison

# Economic Analysis
Section [9]: GDP vs Renewable Energy Correlation
📊 Key Findings
Climate Change:

+1.2°C temperature increase since 1961

Accelerated warming post-2000 (0.3°C/decade)

Energy Transition:

markdown
Copy
1965-1984: 92% Hydropower
2005-2021: 58% Wind/Solar
Economic Correlation:

Strong GDP-renewables correlation (r=0.78)

Notable outliers: NOR (Norway), BRA (Brazil), CAN (Canada)

2022 Energy Mix:

Top performers: Norway (98%), Brazil (85%), Canada (67%)
