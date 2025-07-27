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
   - [uber_with_weather.csv]() Final dataset with simulated weather
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
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/1.PNG) ![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Correlation%20Matrix.png)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/2.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/3.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/4.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/5.PNG)
![](https://github.com/NKBelie/Uber-Fares-Dataset-Analysis/blob/main/Image/Average%20Fare%20by%20Hour%20of%20Day.png)

