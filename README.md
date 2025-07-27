# Personal Introduction
**Names :** NDAYISABA KAMARIZA Belie<br>
**ID :** 27174<br>
**Course:** Introduction to Big Data Analytics<br>
**Concentration:** Software Engineering


# Uber-Fares-Dataset-Analysis
As Uber expands its urban mobility services, understanding the dynamics of fare pricing, trip duration, and temporal patterns is crucial to ensure both customer satisfaction and operational efficiency.

# Problem Statement
This project aims to analyze Uber ride data to identify patterns in fare pricing, ride frequency, and time-based trends. The dataset contains raw and sometimes inconsistent records, making it essential to clean and transform the data before drawing insights. By exploring relationships between fare amounts, trip times, and distances, the goal is to create a clear and interactive Power BI dashboard that helps reveal peak periods, potential pricing inefficiencies, and ride behavior to support data-driven decision-making.

# Introduction
The purpose of this project is to analyze Uber fare data to uncover meaningful patterns and trends in ride behavior. By exploring fare distribution, ride timing, passenger demand, and geographic distribution (if available), the project aims to develop insights that can assist in operational decision-making, pricing strategies, and demand forecasting. This analysis also simulates weather impacts to demonstrate potential external factors influencing Uber rides.
# Methodology
- **Data Source**
[Uber_Fares_Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset) <br>
The dataset (uber.csv) was provided for academic analysis and contains details on Uber rides including fare amount, pickup time, and location.
- **Dataset Used**
   - [Uber.csv](https://drive.google.com/file/d/1JhUHMUhgDmc27c-TLvIGA_PxuNEgKqpa/view?usp=drive_link) Original Dataset
   - [uber_cleaned.csv](https://drive.google.com/file/d/1HQrrn0rAE80b3SakaO-GTBlZaquIIYbB/view?usp=drive_link) Cleaned dataset for Power BI
   - [uber_with_weather.csv](https://drive.google.com/file/d/1ojLtDKI9nmpBc43BDTlQpMbMeXSKDfzH/view?usp=drive_link) Final dataset with simulated weather
- **Tools Used:**
   - **Python (Pandas, NumPy)** – for data analysis and feature engineering and export.
   - **Jupyter Notebook** – for code execution, Data cleaning and visualization
   - **Power BI** – for dashboard creation and interactive visual analytics.
- **Data Cleaning:**
    - Removed invalid or missing values
    - Dropped rows with fare_amount <= 0
- **Feature Engineering:**
   - Extracted hour, day, month, and day_name from pickup_datetime
   - Created is_peak_hour flag (for rush hours)
   - Simulated a weather column with realistic probability (70% Clear, 25% Rain, 5% Snow)
   - Exported the cleaned and enriched dataset for Power BI use.
 - **Power BI Files**
   - [Visualization](https://drive.google.com/file/d/1LueZUUmeW52iJ-MRf8qLbDJM7ucwUFIm/view?usp=drive_link)
   - [Dashboard](https://drive.google.com/file/d/18Q3dyrMbzqOGeO7Rvf7NEtTtpB8sXray/view?usp=drive_link)
# Analysis: Detailed Findings and Statistical Insights
### Descriptive Statistics
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Statistics.PNG)
### Fare Distribution
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/11.PNG)
### Temporal Patterns
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/2.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/8.PNG)
### Simulated Weather Impact
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/14.PNG)
### Geographic Trends
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Map.PNG)

# All Result Image
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Load%20Data%201.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/1.PNG) 
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/2.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/3.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/4.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/5.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Average%20Fare%20by%20Hour%20of%20Day.png)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Correlation%20Matrix.png)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Fare%20Amount%20Boxplot.png)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Fare%20Amount%20vs.%20Distance%20Traveled.png)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/6.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/9.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/10.PNG)

# Dashboard
The Uber Fares Dashboard presents key insights into ride patterns. Most rides are low-cost, with fares under $20, while a few high-value trips suggest longer or premium rides. Ride activity peaks in the evening hours, especially between 5 PM and 8 PM. Fridays and weekends see higher ride demand compared to other days. Over the years, both fare amounts and ride volume have gradually increased. Geographically, the majority of pickups occur in densely populated urban areas such as New York City. These patterns highlight the strong influence of time and location on Uber usage, offering useful insights for pricing and operational planning.

![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Dashboard.PNG)

# Conclusion
The analysis revealed that most Uber fares are low, reflecting short-distance trips, while high fares indicate longer or premium rides. Peak demand occurs during morning and evening rush hours, especially on weekdays. Simulated weather data showed increased fares and ride volume during rain and snow. Geographic trends confirmed that most rides happen in urban centers. These findings highlight the importance of time, location, and external conditions in shaping Uber ride patterns.

# Recommendations
  - Increase driver availability during peak hours (early morning and evening) to meet high demand.
  - Use dynamic (surge) pricing during busy periods and bad weather to manage rider load and maximize profit.
  - Integrate real-time weather data into operations for better forecasting and planning.
  - Focus marketing and promotions in high-demand urban areas where most rides occur.
  - Introduce off-peak discounts to encourage ridership during low-demand times.
  - Regularly monitor ride patterns (hourly, daily, monthly) to adjust pricing, driver shifts, and promotions.
  - Use geographic data to guide driver placement and expand services into under-served but growing areas.
    
