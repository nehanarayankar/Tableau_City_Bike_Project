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

The data for this project can be found at [Citibike Data](https://citibikenyc.com/system-data).

# Data Cleaning Process

**1. Imported Data (12 files)**
   -  Loaded data to Excel
   -  Reviewed for any immediate inconsistencies, missing values, and formatting issues

**2. Handled Missing Values**
   -  Identified missing values across the dataset
   -  Replaced missing values with Average or Median
   -  In some cases, removed rows with missing critical data that could impact analysis

**3. Standardizing Data Formats**
   -  Converted date fields to a consistent format
   -  Ensured numerical data was correctly formatted
   -  Standardized text columns

**4. Removing Duplicates**
   -  Used Excel feature to remove duplicates
   -  Cross-checked if removing duplicates did not affect the data

**5. Filtering Outliers**
   -  Conducted basic outlier detection by reviewing summary statistics to identify anomalies

**6. Data Validation**
   -  Applied data validation rules to ensure future data entries follow expected formats

**7. Creating New Calculated Columns**
   -  Added calculated fields, e.g., trip duration

**8. Preparing Data for Tableau**
   -  Ensured that the cleaned data was in a format suitable for import into Tableau
   -  Saved the cleaned dataset as a new Excel file or CSV, removing unnecessary metadata or formatting to optimize performance when importing into Tableau

## Visualization

### Tableau:
- **Dashboard Creation:** Utilized Tableau to create interactive dashboards visualizing the Citibike dataset.
- **Filters and Interactivity:** Incorporated dynamic filters (e.g., date range, user type, station location), allowing users to interact with the data and explore trends in trip duration, station usage, and user demographics.

# Analysis

- There are several issues reported with the NYC Citi bike service, and with the analysis here, I prepare to answer a few questions and provide some recommendations for improvements.
   -  Clean data is visualized using Tableau, and each visualization provides a unique perspective on bike usage patterns, user behavior, and station performance.

**1. Total No of Bike Rides**
-   The total number of bike rides in the dataset gives a clear view of the overall adoption and usage of the Citi Bike program. This is a crucial indicator of the program's growth over time, this number gives the **Total Number of Bike Rides** taken by cyclists in the year 2022.
  
  ![Total Bike Rides](https://github.com/user-attachments/assets/b78e1557-e599-466e-abfc-69927538156b)

- Total bike rides reported in 2022 was 331,150.
- This also shows that the number of users who subscribe to the app is 68% while the number of users who do not is approximately 32%, which shows 32% of users might not be regular users.


**2. Number of Bike Rides in Every Month**
-   This worksheet shows monthly ride trends, highlighting fluctuations in usage throughout the year.
  
  ![No of Rides Every Month (1)](https://github.com/user-attachments/assets/bd1cc9f2-ab01-434b-ac09-e68e0ffe58b2)

- August and October reported the highest number of bike rides, while April and December reported the lowest.
  
**3. Average Ride Duration by User Type**
-   This visualization breaks down the average number of rides by user type (e.g., Subscriber vs. Customer).

![Avg Rides](https://github.com/user-attachments/assets/0981fd48-b7cc-498f-b0ea-10c094d7cf9d)



- Subscribers should ideally have a higher frequency of activity on the bikes, but given the issues within the system, Customers here are the high-frequency users.
- This insight is useful and can be leveraged in targeting different user groups with tailored marketing and service offerings



