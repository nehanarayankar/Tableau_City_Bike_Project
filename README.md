# Tableau City Bike Project
Data Visualization Project 

# Introduction

Welcome to my City Bike Share Data Analysis project! 
I explore and analyze data from the New York City bike-sharing system in this repository to uncover insights into bike usage patterns, peak hours, customer demographics, and environmental impacts. By leveraging data visualization tools like Tableau and conducting detailed statistical analysis, this project aims to provide actionable insights that can help optimize bike-sharing programs, improve city transportation infrastructure, and encourage sustainable commuting. Dive into the data and visualizations to explore the trends that shape urban mobility.

Citi Bike is a bike-sharing program in New York City that provides a convenient, eco-friendly, and affordable alternative to traditional transportation. Launched in May 2013, it has grown into one of the largest and most successful bike-sharing systems in the United States. The program operates through a partnership between Citigroup and the Metropolitan Transportation Authority (MTA), offering a fleet of blue bikes and docking stations located throughout the city.

Citi Bike is available to both residents and visitors, who can sign up for a membership ranging from one day to one year. After registering, users can access bikes by using a membership card or the Citi Bike mobile app to unlock a bike from any station. The bikes must be returned to a docking station within the designated time to avoid extra charges.

This bike-sharing program is especially useful for short trips and navigating busy urban areas, providing a sustainable mode of transportation. Citi Bike promotes health and wellness by encouraging cycling and offering users an alternative to car travel. It has also helped foster a sense of community, with users enjoying scenic rides around the city’s parks and streets. By reducing congestion and supporting active lifestyles, Citi Bike has become an important part of New York City’s transportation landscape.


# Problem

After establishing within a few years, Citi Bike faced several complaints regarding its inefficient bike redistribution system, leading to imbalances between stations. During peak commuting hours, residential areas often run out of bikes in the morning, while commercial areas face shortages in the afternoon. Numerous recent tweets and articles reflect this frustration, highlighting the issues customers experience with bike availability throughout the day.


# Data and Data Cleaning

The data for this project can be found at https://citibikenyc.com/system-data

Data Cleaning Process
1. Imported Data (12 files) 
	a. Loaded data to Excel
	b. Reviewed for any immediate inconsistencies, missing values and formatting issues
2. Handled Missing Values
	a. Identified missing values across the dataset 
	b. Replaced missing values with Average or Median
	c. In some cases, removed rows with missing critical data that could impact analysis
3. Standardizing Data Formats
	a. Converted date fields to a consistent format
	b. Ensured numerical data was correctly formatted
	c. Standardized text columns
4. Removing Duplicates
	a. Used Excel feature to remove duplicates
	b. Crossed if removing duplicates did not affect the data
5. Filtering Outliers
	a. Conducted basic outlier detection by reviewing summary statistics to identify anomalies
6. Data Validation:
	a. Applied data validation rules to ensure future data entries follow expected formats
7. Creating New Calculated Columns:
	a. Added calculated fields, e.g., trip duration 
8. Preparing Data for Tableau:
	a. Ensured that the cleaned data was in a format suitable for import into Tableau.
	b. I saved the cleaned dataset as a new Excel file or CSV, removing unnecessary metadata or formatting to optimize performance when importing it into 		tableau





