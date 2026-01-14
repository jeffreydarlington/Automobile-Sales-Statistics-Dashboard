# Final Project Overview

## Analyzing the Impact of Recession on Automobile Sales

## Project Summary

You are working as a **Data Scientist at XYZAutomotives**, tasked with analyzing historical automobile sales data to understand how **economic recessions impact vehicle sales**. The objective of this project is to generate **data-driven insights and visualizations** that help company directors better understand sales behavior during recession and non-recession periods.

The analysis is presented through **exploratory visualizations** and an **interactive dashboard**, making the findings accessible to both technical and non-technical stakeholders.

---

## Dataset Overview

This project uses a **synthetically generated dataset** created exclusively for this assignment. No real-world data has been used.

The dataset focuses on automobile sales trends across multiple recession periods:

### Recession Periods Covered

* **1980**
* **1981–1982**
* **1991**
* **2000–2001**
* **2007–2009** (Global Financial Crisis)
* **February–April 2020** (COVID-19 impact)

---

## Data Description

The dataset contains the following variables:

* **Date** – Month-end date of the sales observation
* **Recession** – Binary indicator (1 = recession, 0 = non-recession)
* **Automobile_Sales** – Number of vehicles sold
* **GDP** – Per-capita GDP (USD)
* **Unemployment_Rate** – Monthly unemployment rate
* **Consumer_Confidence** – Synthetic index representing consumer sentiment
* **Seasonality_Weight** – Seasonal effect on automobile sales

  * > 1: Higher-than-average expected sales
  * < 1: Lower-than-average expected sales
  * ≈ 1: Neutral seasonal impact
* **Price** – Average vehicle price
* **Advertising_Expenditure** – Company advertising spend
* **Vehicle_Type** – Vehicle category

  * Superminicar
  * Smallfamilycar
  * Mediumfamilycar
  * Executivecar
  * Sports
* **Competition** – Measure of market competition
* **Month** – Extracted from Date
* **Year** – Extracted from Date

---

## Project Structure

The project is divided into **two major parts**:

---

## Part 1: Exploratory Data Visualization

**Tools:** Pandas, Matplotlib, Seaborn, Folium

### Objective

Analyze historical trends in automobile sales during recession and non-recession periods using static and exploratory visualizations.

### Tasks

* **Task 1.1:** Line chart showing yearly automobile sales trends
* **Task 1.2:** Correlation between advertising expenditure and sales during non-recession periods
* **Task 1.3:** Comparison of vehicle-type sales during recession vs. non-recession periods
* **Task 1.4:** Subplots comparing GDP trends during recession and non-recession periods
* **Task 1.5:** Bubble plot showing the impact of seasonality on automobile sales
* **Task 1.6:** Scatter plot analyzing vehicle price vs. sales volume during recessions
* **Task 1.7:** Pie chart showing advertising expenditure during recession vs. non-recession periods
* **Task 1.8:** Pie chart showing advertising expenditure by vehicle type during recessions
* **Task 1.9:** Line plot analyzing the effect of unemployment rate on vehicle sales during recessions

---

## Part 2: Interactive Dashboard

**Tools:** Plotly, Dash

### Objective

Create an **interactive dashboard** that allows directors to explore recession and yearly sales data dynamically without requesting new visualizations.

### Dashboard Features

* Dropdown-based filtering
* Dynamic charts and reports
* Recession vs. yearly performance comparison

### Tasks

* **Task 2.1:** Create a Dash application with a meaningful title
* **Task 2.2:** Add dropdown menus with appropriate options
* **Task 2.3:** Create output containers for dynamic visualization
* **Task 2.4:** Implement callbacks to update charts based on user input
* **Task 2.5:** Display recession-based report statistics
* **Task 2.6:** Display yearly-based report statistics

---

## Key Skills Demonstrated

* Data cleaning and transformation
* Exploratory data analysis (EDA)
* Data visualization best practices
* Dashboard development with Dash
* Business-focused analytical storytelling

---
