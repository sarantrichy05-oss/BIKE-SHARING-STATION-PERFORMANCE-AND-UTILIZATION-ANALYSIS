# Bike Sharing Station Performance and Utilization Analysis

An interactive Power BI dashboard analyzing bike-sharing station data to understand station performance, bike availability, and utilization patterns across different cities and time periods.

---

##  Table of Contents

* Project Overview
* Data Source
* Tools & Technologies
* Data Cleaning & Preparation
* Data Modeling & DAX
* Exploratory Data Analysis (EDA)
* Key Insights
* Recommendations
* How to Use
* Requirements

---

##  Project Overview

This project analyzes bike-sharing station data using **Microsoft Power BI** to evaluate operational performance and urban mobility trends.

The main objective of this analysis is to identify station activity, evaluate bike availability, measure utilization efficiency, and detect underperforming locations. By transforming raw data into an interactive dashboard, the project enables better decision-making for optimizing bike distribution and improving service availability.

---

##  Data Source

The dataset used in this project is an **Open Bike Sharing Dataset**, which contains detailed information about bike stations across multiple cities.

**Domain:** Transportation / Urban Mobility Analytics

###  Key Variables

* Station Number
* Station Name
* Address
* Status (Open / Closed)
* Bike Stands (Capacity)
* Available Bikes
* Available Bike Stands
* Last Update (Date & Time)
* Latitude
* Longitude

Additional columns such as **Year and Month** were created for time-based analysis.

---

##  Tools & Technologies

**Visualization Tool:** Power BI Desktop

Power BI was used for:

* Data Cleaning and Transformation (Power Query)
* Data Modeling (Star Schema)
* DAX Calculations
* Interactive Dashboard Creation

---

##  Data Cleaning & Preparation

Several preprocessing steps were performed:

* Removed duplicate records
* Handled missing values
* Standardized column formats
* Extracted Year and Month from date column
* Created custom columns for better analysis
* Split station name and number for clarity

A structured dataset was prepared for efficient analysis and reporting.

---

##  Data Modeling & DAX

A **Star Schema** data model was implemented:

* **Fact Table:** Contains measurable metrics such as available bikes, empty stands, and capacity
* **Dimension Tables:** Include station details, location, and date information

###  Key DAX Measures

* Active Stations
* Closed Stations
* Total Available Bikes
* Total Bike Stands
* Empty Stands
* Utilization Rate
* Active vs Closed Percentage

---

##  Exploratory Data Analysis (EDA)

The analysis focused on answering key business questions:

* Which stations are active vs closed?
* How are bikes distributed across cities?
* Which locations have high or low utilization?
* How does station performance vary over time?
* Where are underperforming stations located?

---

##  Dashboard Visualizations

The Power BI dashboard includes:

* Total Available Bikes by City
* Active vs Closed Stations Distribution
* Monthly Station Activity Trend
* Utilization Rate Analysis
* Bike Stand Distribution by Location
* Geographical Map (Latitude & Longitude)

---

##  Key Insights

* Over **92% of stations are active**, indicating strong operational availability
* Cities like **Lyon and Toulouse** show higher utilization rates
* Some cities have **high capacity but low usage**, indicating inefficiency
* Bike-sharing systems are highly concentrated in **European regions**
* Demand varies across locations, highlighting the need for optimized distribution

---

##  Recommendations

* Increase bike availability in high-demand locations
* Redistribute bikes from low-demand to high-demand areas
* Improve maintenance of closed stations
* Expand infrastructure in high-utilization cities
* Monitor station performance regularly for optimization

---

##  How to Use

1. Download the Power BI (.pbix) file from this repository
2. Open using Microsoft Power BI Desktop
3. Explore the interactive dashboard
4. Use filters and slicers to analyze:

   * City / Location
   * Station Status
   * Time (Year / Month)



##  Requirements

* Microsoft Power BI Desktop

---


