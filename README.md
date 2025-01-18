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
  
  ![No of Rides Every Month](https://github.com/user-attachments/assets/e0921a5f-7e46-4ad1-af24-6b07bd4d0fb0)

- August and October reported the highest number of bike rides, while April and December reported the lowest.
  
**3. Number of Rides & Avg Duration by User Type**
-   This visualization breaks down the number of rides by user type (e.g., Subscriber vs. Customer).

![No Rides   Avg Duration by Users](https://github.com/user-attachments/assets/ba71b6d9-ca45-4093-89c3-38365660a700)


- Subscribers tend to have a higher frequency of rides, which indicates that regular users rely more heavily on the system, while occasional customers use it sporadically.
- This insight is valuable and can be leveraged to target different user groups with tailored marketing and service offerings.


**4. Number of Trips in a Week**
-   Analyzing trips by the day of the week helps identify peak usage times.

![No of Trips in a Week](https://github.com/user-attachments/assets/aa567b26-d40e-41f5-8926-33dab834fa77)


-   The visual shows how weekday vs. weekend trips differ, weekdays show a very consistent activity and bike usage, given people use bikes to commute, while weekends show a higher usage indicating increased leisure use.


**5.Top 10 Stations Most Trips and Duration** 
-   This visualization highlights the most popular stations in terms of the number of trips and total duration. 

![Top 10 Starting Stations (1)](https://github.com/user-attachments/assets/be0118ac-6fb8-4ffe-a2d6-35ee4022cba8)

![Top 10 Ending Stations (1)](https://github.com/user-attachments/assets/860fb907-5eb6-4c03-807e-cb03a46d2641)


-   Stations near transportation hubs, business districts, and parks are typically the busiest, providing insight into the areas with the highest demand and potential need for more bikes. These trends often 
 mirror each other, with some locations showing higher start points or return rates, signaling popular routes or areas where users prefer starting or ending their trips.
-   Using this insight, the Company can place additional bikes as required at stations with the most activity.


**6.Trip Duration by Month**
-   This visualization analyzes trip duration over every month in the year, helping us understand how trip lengths fluctuate over time.

![Trip Duration by Month](https://github.com/user-attachments/assets/b1e7425e-9b38-47cf-a59b-49a0d2e979fb)

-   This visualization helps us understand that subscribers who tend to be regular users take shorter trips while, on the other hand, leisure trips seem to show longer durations.

**7. Trips by UserType and User Gender**
-   This worksheet provides a gender breakdown of trips by user type. It shows differences in trip patterns between male and female riders, as well as between subscribers and casual users

![Type and Gender Trips](https://github.com/user-attachments/assets/ae75967a-0a2f-40cf-8f38-64ab036a4a19)


-   These insights can be used to create more inclusive experiences, focusing on gender-specific needs or preferences.

**8. Station Maps**
-   The start station and end station map visualizes the geographic distribution of trips based on where they began.

![Starting Stations](https://github.com/user-attachments/assets/a60e1524-e093-412e-ac98-796a433217c3)

![Ending Stations](https://github.com/user-attachments/assets/2f59dbb8-7947-4e1d-b7f7-fda722aac068)


-   This analysis helps identify high-density areas where bike stations are clustered and allows for the optimization of bike availability at key locations.


## Recommendations

Based on the insights gathered from the data analysis, here are several key recommendations to improve the Citi Bike program's efficiency, user experience, and growth:

**1.Optimize Bike Distribution**
-   **Insight:** The analysis of start and end stations shows that certain locations experience higher trip volumes than others, often creating imbalances in bike availability.
-   **Recommendation:** Implement a dynamic bike redistribution system that ensures bikes are efficiently allocated across stations based on demand patterns. This can be achieved through real-time data integration, helping to meet peak demand in high-traffic areas and reduce underutilization at less popular stations.

**2. Enhance User Engagement through Targeted Marketing**
-   **Insight:** The comparison of ride frequency by user type (Subscriber vs. Customer) suggests that subscribers are more likely to use Citi Bike on a regular basis than occasional customers, who seem to use the bikes for leisure activities.
-   **Recommendation:** Develop targeted marketing campaigns to convert occasional users into subscribers. For example, offer time-limited promotions, discounts on monthly subscriptions, or personalized recommendations based on usage patterns. This would help increase user retention and the program's overall adoption.


**3.Increase Awareness and Accessibility for Female Riders**
-   **Insight:** The analysis of gender distribution suggests that male riders dominate the program, with fewer female riders using the service.
-   **Recommendation:** Launch initiatives to attract more female riders, such as partnerships with local organizations, gender-inclusive marketing campaigns, or safety-focused programs (e.g., bike safety workshops and improved station lighting). This could help create a more inclusive and balanced user base.

**4. Implement Seasonal Pricing and Discounts**
-   **Insight:** The analysis of ride trends across months indicates significant seasonality in usage
-   **Recommendation:** Introduce seasonal pricing strategies that offer discounts during off-peak months or incentivize usage during slower months through promotional offers, encouraging year-round use of the service.

  **5.Integration of Weather Data for Improved Planning**
  -   **Insight:** Weather patterns have a clear impact on bike usage, with higher usage during favorable weather conditions.
  -   **Recommendation:**  Integrate weather data into operational planning to anticipate changes in demand. For example, increase bike availability on days with favorable weather forecasts or adjust marketing efforts to promote biking during the most weather-friendly days.




