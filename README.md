# Europe Economic Dashboard

## Overview
An interactive Shiny dashboard that visualizes socioeconomic indicators for Eastern and Western European countries from 2010-2021. The dashboard provides comprehensive analysis of GDP per capita, Gini coefficient, unemployment rates, and life expectancy across different European regions.

## Features
- **Trend Analysis**: Multi-line charts showing temporal changes in key indicators
- **Comparative Analysis**: Bar charts displaying percentage changes between selected years
- **Correlation Analysis**: Scatter plots examining relationships between economic indicators
- Interactive filtering by country, region, and year range
- Responsive design with detailed information panels

## Screenshots



### Trend Analysis
![Screenshot 2025-07-09 165522](https://github.com/user-attachments/assets/86436747-3554-48b2-9cdb-ae4c850f6467)
![Screenshot 2025-07-09 165508](https://github.com/user-attachments/assets/6dba6595-0fb9-4a45-a68d-d6daad5c4beb)
![Screenshot 2025-07-09 165541](https://github.com/user-attachments/assets/3ffe3238-0392-404f-b318-6608cf22ab72)


### Comparative Analysis
![Screenshot 2025-07-09 165725](https://github.com/user-attachments/assets/409dc08b-11fc-4b62-95f2-013feae8f5dc)
![Screenshot 2025-07-09 165657](https://github.com/user-attachments/assets/96513e1c-5fd0-4858-b7c9-863559dda4b4)
![Screenshot 2025-07-09 165605](https://github.com/user-attachments/assets/0d97b606-334d-49bb-a41b-92fe331cb77c)

### Correlation Analysis
![Screenshot 2025-07-09 165736](https://github.com/user-attachments/assets/7b683e95-ca76-4db1-b60a-f90ffe22c832)



## Countries Covered
**Eastern Europe**: Armenia, Georgia, Poland, Slovak Republic, Romania  
**Western Europe**: Italy, Sweden, Austria, Belgium, France

## Data Source
All data is sourced from the World Bank API, covering the period 2010-2021.

## Research Questions Addressed
1. How has GDP per capita evolved in Eastern vs Western European countries?
2. What are the trends in income inequality (Gini index) across regions?
3. How have unemployment rates changed over the decade?
4. What are the life expectancy trends and their correlation with economic indicators?

## Installation & Setup

### Prerequisites
- R (version 4.0 or higher)
- RStudio (recommended)

### Required Packages
```r
install.packages(c(
  "shiny",
  "shinydashboard", 
  "shinydashboardPlus",
  "plotly",
  "ggplot2",
  "dplyr",
  "readr",
  "httr2"
))
```

### Running the Application
1. Clone this repository:
2. Open the project in RStudio
3. Install required packages (if not already installed)
4. Run the application:
 

## Usage
1. Use the sidebar to select regions, countries, and year ranges
2. Navigate through different analysis tabs:
   - **Trend Analysis**: View time series for each indicator
   - **Comparative Analysis**: Compare percentage changes between countries
   - **Correlation Analysis**: Explore relationships between GDP and life expectancy

## Technical Details
- **Framework**: R Shiny with shinydashboard
- **Visualization**: ggplot2 with plotly for interactivity
- **Data Processing**: dplyr for data manipulation
- **API Integration**: httr2 for World Bank API calls

## Key Insights
- Western European countries generally show higher GDP per capita and life expectancy
- Armenia showed significant improvement in income equality around 2018 (post-Velvet Revolution)
- COVID-19 impact visible in 2020 life expectancy data across all countries
- Strong positive correlation between GDP per capita and life expectancy

## Future Enhancements
- Add more countries and regions
- Include additional economic indicators
- Implement predictive modeling
- Add export functionality for charts and data

## Author
Ioane Meparishvili
Management Student | Business Analyst | Finance & AI Enthusiast
## Contact
Ioane Meparishvili - meparishvili.ioane.work@gmail.com  
