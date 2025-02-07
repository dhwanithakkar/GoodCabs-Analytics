# 🚕 GoodCabs (Transportation & Mobility Analytics)

## 🚀 Project Overview  
GoodCabs, a taxi service provider, focuses on empowering local drivers by enabling them to earn a stable income within their own cities while delivering top-notch service to customers. Operating in ten tier-2 cities across India, the company’s leadership seeks to evaluate its performance based on essential metrics such as ride volume, customer satisfaction, retention rates, trip patterns, and the proportion of new versus returning passengers. To enhance **data-driven decision-making**, GoodCabs integrates **Power BI** into its operations for insightful analysis and strategic improvements.

## Objective
This report enables **data-driven decision-making**, providing valuable insights to support various scenarios.
#### Click here to review the full [Report](https://app.powerbi.com/view?r=eyJrIjoiYWQ5ZWYxOTktYmQ2Yi00MzMzLWI4MzctZjRkYTM3YTgwNjM1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9).

## 📊 Data & Analytics Tools
- **MySQL** – Data extraction, transformation & management  
- **Power BI Desktop** – Dashboard creation & data visualization  
- **Excel** – Data preprocessing & organization  
- **DAX (Data Analysis Expressions)** – Advanced calculations & measures

## 📊 Dataset Overview  
NOTE: Imported the datasets from Mysql database ('trips_db' and 'targets_db') to PowerBI

This dataset consists of **dimension tables** (static data) and **fact tables** (transactional data). 
### 🗂 Dimension Tables (Reference Data)  
- **`dim_city`** – City-specific details, enabling location-based analysis. 
- **`dim_date`** – Date-specific details that enable time-based grouping and analysis, helping to identify patterns across days, months, and weekends versus weekdays..  
- **`dim_repeat_trip_distribution (Aggregated Data)`** – provides a breakdown of repeat trip behavior, aggregated by month and city.
- **'city_target_passenger_rating'** - target average passenger rating that Goodcabs aims to achieve for each city, used to monitor customer satisfaction.

### 📊 Fact Tables (Transactional Data)  
- **`fact_passenger_summary (Aggregated Data)`** – Aggregated summary of passenger counts for each city by month.
- **`fact_trips`** – detailed information on each individual trip, including trip-specific metrics like distance, fare, and ratings, which can be used for granular trip-level analysis.
- **`monthly_target_new_passengers`** – target number of new passengers Goodcabs aims to acquire in each city for the specified month, supporting growth tracking.
- **`monthly_target_trips`** - target number of total trips Goodcabs aims to achieve for each city and month, enabling assessment of trip volume performance.

## Data Modelling
We have used the Snowflake schema. 
![image](https://github.com/user-attachments/assets/135c6cd7-eddb-4e7d-8dfb-a09a6e7901f2)

## 📊 Dashboards Overview  
- **Home Page** – This is the central hub for seamless navigation.  
- **Business Overview** – This page provides an overview of the business performance, highlighting revenue trends, total number of trips etc, both on a monthly basis and across different cities.  
- **Passenger & Rating insights** – This illustrates the distribution of our customers, the repeat passenger rate, and the ratings received by both drivers and passengers.
- **Target Analysis** – This indicates whether the targets were achieved or not.Performance breakdown by customer segments.  

## Overview
![Image](https://github.com/user-attachments/assets/93d7b846-b437-4a62-98e0-f77617fdcf8e)

## Business Overview
![Image](https://github.com/user-attachments/assets/b395efca-68c9-48bb-a933-01b4a4b53bc2)

## Passenger & Rating insights
![Image](https://github.com/user-attachments/assets/d45cb58f-a66c-4aed-856a-0989e0fe9561)

## Target Analysis
![Image](https://github.com/user-attachments/assets/9bd087bb-7fb6-40cf-bb55-5bf9f61a79fb)

## 🎯Takeaways & Learning Outcomes:
This project significantly enhanced my technical and storytelling capabilities by enabling me to:
- Approach operational data with a strategic, oriented perspective.
- Apply analytical tools to solve real-world challenges with impactful solutions.
- Articulate insights effectively to stakeholders.
