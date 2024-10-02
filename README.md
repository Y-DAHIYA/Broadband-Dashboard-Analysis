# Broadband-Dashboard-Analysis
## Overview
This repository contains a Power BI dashboard project that analyzes broadband access, costs, and socio-economic factors across various US counties. The dashboard features interactive visuals, such as maps, line charts, and pie charts, with filters and slicers for enhanced user interactivity.

## Features
- **Map Visual** : Displays broadband availability across US counties.
- **Pie Chart**: Shows the distribution of average broadband costs by state.
- **Donut Chart**: Visualizes the distribution of broadband access across different states.
- **Line Chart**: Compares average download speed and average unemployment rate.
- **Stacked Bar Chart**: Represents the average unemployment rate by state.
- **Slicers**: Allow for dynamic filtering based on county, state, unemployment rate, and population.
- **Interactive Cards**: Summarizes key metrics like :
  - Average unemployment rate
  - Average download speed
  - Average number of people without internet access
  - Average lowest broadband cost
  - Broadband availability 
  - Lowest broadband access

## Dataset Overview
This dataset provides comprehensive information about broadband access, demographic, and socio-economic factors across various counties in the United States. The key columns in the dataset include:

- **`full_name`**: County and state.
- **`county`**: County label.
- **`state`**: US state.
- **`state_abr`**: State abbreviation.
- **`population`**: Population (IMLS set, 2019 US Census estimate).
- **`unemp`**: Unemployment rate, Bureau of Labor Statistics, spring 2020.
- **`health_ins`**: Percent without health insurance, US Census Bureau ACS.
- **`poverty`**: Poverty rate, US Census Bureau ACS.
- **`SNAP`**: Percent received SNAP, US Census Bureau ACS.
- **`no_comp`**: Percent with no home computer, US Census Bureau ACS.
- **`no_internet`**: Percent with no home internet, US Census Bureau ACS.
- **`home_broad`**: Percent with home broadband, US Census Bureau ACS.
- **`broad_num`**: Number of broadband providers, bbn data (from IMLS set).
- **`broad_avail`**: Population for whom broadband is available (%), bbn data (from IMLS set).
- **`broad_cost`**: Lowest cost per month, bbn data (from IMLS set).
- **`population_bbn`**: Population (from BBN set).
- **`price_bbn`**: Lowest broadband cost per month (from BBN set).
- **`wired_bbn`**: Number of Wired (Cable, Copper, DSL, Fiber) providers (from BBN set).
- **`provide_bbn`**: Number of Providers of any technology present in a zip code (BBN set).
- **`all25_bbn`**: Number of Providers (any technology) present in a zip code offering speeds of at least 25 Mbps Download / 3 Mbps.
- **`downave_bbn`**: Average Download Speed via M-Lab Speed Tests, rolling 12 months.
- **`access_bbn`**: Percent of the Population that has Access to Terrestrial (Wired + Fixed Wireless) Broadband (25 Mbps Download / 3 Mbps).
- **`slowfrac_bbn`**: Fraction of the population in zip codes where average download speed is less than 6 Mbps.

### New Measures Created
- Access to Terrestrial
- Average Download Speed
- Average Lowest Broadband Cost
- Average No Internet Access
- Average Unemployment Rate
- Broadband Available
- Highest Unemployment Rate
- Lowest Broadband Access

## Files in the Repository
- **Dashboard File**: `Dashboard Power BI` (Power BI file).
- **Data File**: `broadband_access.csv` (CSV file containing the dataset).
- **README.md**: This file, providing an overview of the project.

## How to Use
1. Clone or download the repository.
2. Open the Power BI file to explore the dashboard.
3. Use the slicers and filters to drill down into the data for specific states or counties.
4. Explore the interactive visuals for detailed insights into broadband access and socio-economic conditions.

## Technologies Used
- **Power BI**: For building the interactive dashboard.
- **GitHub**: Version control for the project.
