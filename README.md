# World-Population-Analysis
# Project Overview  
This project analyzes global population trends from 1970 to 2022 using Power BI. The objective is to explore population growth, regional differences, and key insights using interactive visualizations.  
# Problem Statement  
The goal of this project is to analyze and visualize world population trends from 1970 to 2022 using Power BI.  
•	Total World Population  
•	Top 10 Most Populated Countries in 2022  
•	World Population Over Time  
•	Population Density by Country  
•	Population by Continent  
# Tools Used
•	**Power BI** for visualization and dashboard creation.  
•	**Excel/CSV** as a data source.  

# Data Sources  
The dataset contains population data for 234 countries from 1970 to 2022, along with additional metrics such as area, population density, and growth rate.  
**Data Fields:**
•	**Rank**: The global population rank of the country/territory.  
•	**CCA3**: The three-letter country code.  
•	**Country/Territory**: Name of the country or territory.  
•	**Capital**: The capital city of the country/territory.  
•	**Continent**: The continent where the country is located.  
•	**Population Data**: Population counts for the years 2022, 2020, 2015, 2010, 2000, 1990, 1980, and 1970.  
•	**Area (km²)**: The total land area of the country/territory in square kilometers.  
•	**Density (per km²)**: Population density calculated as people per square kilometer.  
•	**Growth Rate**: The annual population growth rate.  
•	**World Population Percentage**: The percentage of the world's population that resides in the respective country.  

# Data Cleaning and Analysis  
Data cleaning was performed in power bi power query to ensure data integrity and consistency.  
Before analyzing the dataset, we performed the following data cleaning steps:  
•	**Handled Missing Values**: Ensured that all necessary columns had valid data. Since the dataset had no missing values, no imputation was required.  
•	**Renamed Columns**: Standardized column names for better readability and consistency.   
•	**Converted Data Types**: Ensured that numeric columns (population, area, density, etc.) were stored as integers or floats for efficient processing.  
•	**Unpivoted Yearly Population Data**: Transformed the dataset from wide format (separate columns for each year) into a long format using the melt (unpivot) function for better analysis and visualization. Example: Population data was stored in separate columns for different years (2022, 2020, 2015, etc.), we reshaped the dataset using unpivoting (melt function) to bring all years under a single column.  

# Visualization Used in Power BI  
1.	Total World Population (Card Visualization)
2.	Slicers: To filter data by country dynamically.
3.	Sum of 2022 Population by Country (Bar Chart)
4.	World Population Growth (1970-2022) (Line Chart)
5.  Population Density by Country (Map)
6.	Population by Continent (Pie Chart)

# Exploratory Data Analysis  

•	Population Growth Trends Over Different Time Periods  
•	Identify the Most Populated Country/Region  
•	Peak Population Growth Years and Decades  
•	Population Growth Trends by Continent  
•	Comparison of Population Density Across Countries  

# Results  
![Alt text](https://github.com/vrushaliwaykar/World-Population-Analysis/blob/main/Dashboard.PNG?raw=true)

# Conclusion  
The analysis of world population trends (1970-2022) reveals significant growth, with major contributions from countries like China and India. Population distribution varies across continents, impacting resources and development. Interactive Power BI dashboards help visualize these trends for better decision-making.



   






