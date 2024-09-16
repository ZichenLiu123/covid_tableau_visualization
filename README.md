# COVID-19 Data Exploration and Visualization Project

## Project Overview
This project explores global COVID-19 data to analyze trends in infection rates, death rates, and vaccination progress. Using a variety of SQL techniques, the data is cleaned, transformed, and explored. Additionally, visualizations were created to offer insights into the global impact of the pandemic, helping to illustrate key trends and patterns.

![image](https://github.com/user-attachments/assets/b5bd9dde-19ef-43c3-bfb6-f9db5a775f39)

## Key Skills Demonstrated
- **Joins**: Combined COVID-19 deaths and vaccination data for comprehensive analysis.
- **Common Table Expressions (CTEs)**: Used to perform complex calculations, including rolling vaccination totals.
- **Temp Tables**: Stored intermediate results for further calculations.
- **Window Functions**: Employed to calculate running totals of vaccinations and perform partitioned aggregations.
- **Aggregate Functions**: Utilized to calculate key statistics like total cases, deaths, and infection rates.
- **Data Type Conversion**: Ensured accuracy by converting data types for numerical and date-based calculations.
- **Views**: Created for easy access to processed data for further analysis and visualization.
- **Data Visualization**: Generated dashboard in Tableau to visually represent infection rates, death counts, and vaccination progress.

## Key Analyses
1. **Total Cases vs Total Deaths**: 
   - Calculated the likelihood of dying from COVID-19 based on total cases and deaths, focusing on specific countries like the United States.

2. **Total Cases vs Population**: 
   - Analyzed the percentage of each population infected by COVID-19 in different countries.

3. **Highest Infection Rates**:
   - Identified countries with the highest infection rates relative to their population size.

4. **Death Count per Population**:
   - Ranked countries and continents by death counts relative to their population.

5. **Global Aggregates**:
   - Summarized global totals for cases and deaths, along with the death percentage for COVID-19 cases worldwide.

6. **Vaccination Progress**:
   - Tracked the percentage of the population vaccinated against COVID-19, using window functions to calculate rolling totals of vaccinations.

## Data Visualization
The project includes visualizations that highlight:
- Trends in COVID-19 infections and deaths by country and continent.
- Rolling vaccination totals and the percentage of the population vaccinated.
- Comparisons of infection rates and death counts across different regions.
  
These visualizations provide a clear representation of how COVID-19 affected populations globally and the progress of vaccination campaigns.

## Advanced Techniques
- **CTEs**: Used for breaking down complex queries and creating intermediate results for vaccination calculations.
- **Temp Tables**: Employed to store vaccination data and perform further analysis, such as calculating the percentage of the population vaccinated.
- **Views**: Created to store cleaned and processed data for use in visualization tools.

## Tech Stack
- **SQL Server**
- **SQL Queries**: Data exploration, aggregation, CTEs, temp tables, joins, and window functions
- **Visualization Tools**: Tableau
- 
## Business Impact
This project provides in-depth analysis and visual insights into the global impact of COVID-19. By focusing on infection rates, death rates, and vaccination progress, the insights can support public health decision-making, resource allocation, and further research into pandemic trends.

## Acknowledgments
Special thanks to data providers for COVID-19 deaths and vaccination datasets, and to the SQL and data visualization communities for offering valuable resources for this analysis.
