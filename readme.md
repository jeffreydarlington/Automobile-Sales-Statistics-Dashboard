This README file provides an overview of the "Automobile Sales Statistics Dashboard" project, based on the provided assignment files.

# Automobile Sales Statistics Dashboard

## Project Overview

This project focuses on analyzing historical automobile sales data to understand the impact of recession periods on sales performance. It is divided into two main parts:

1. 
**Data Visualization & Analysis**: Using Python libraries to identify trends and patterns in automobile sales during various recessionary and non-recessionary periods.


2. 
**Interactive Dashboard Development**: Building a web-based dashboard using Dash and Plotly to allow users to interactively explore the data through different visualizations.



## Data Description

The dataset contains monthly automobile sales records and economic indicators, including:

* **Date & Year**: Time of the observation.
* **Recession**: A binary indicator (1 for recession, 0 for normal).
* **Automobile_Sales**: Number of vehicles sold.
* **GDP & Unemployment_Rate**: Key economic health indicators.
* **Consumer_Confidence**: An index reflecting consumer spending sentiment.
* **Vehicle_Type**: Categories such as Supperminicar, Smallfamilycar, Mediumfamilycar, Executivecar, and Sports.
* **Advertising_Expenditure**: Company spending on advertisements.

## Objectives

* Develop informative visualizations using **Matplotlib**, **Seaborn**, and **Folium**.


* Analyze the fluctuation of average automobile sales from year to year.


* Compare sales performance across different vehicle types during recession vs. non-recession periods.


* Create an interactive **Dash** application with dropdown menus for "Yearly Statistics" and "Recession Period Statistics".



## Key Features

### Part 1: Analysis Tasks

* 
**Line Charts**: To show annual fluctuations in average sales.


* 
**Bar Charts**: To compare average vehicles sold by type during recessions.


* 
**Scatter Plots**: To observe the relationship between GDP and sales.


* 
**Pie Charts**: To visualize total advertisement expenditure by vehicle type.



### Part 2: Dashboard Components

The dashboard includes the following interactive elements:

* 
**Dropdown Menus**: For selecting the type of statistics (Yearly or Recession) and the specific year.


* **Dynamic Graphs**:
* Line chart for average automobile sales over time.


* Bar chart for average vehicles sold by type.


* Pie chart for total expenditure share by vehicle type during recessions.





## Installation and Setup

To run this project, ensure you have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn folium dash plotly

```

## How to Run

1. 
**Analysis**: Open the Jupyter Notebook (`DV0101EN-Final-Assign-Part1-v1.jupyterlite.ipynb`) to view the initial data analysis and static plots.


2. 
**Dashboard**: Run the Python script to launch the interactive dashboard:


```bash
python DV0101EN-Final-Assign-Part-2-Questions.py

```


3. Access the dashboard in your web browser at `http://127.0.0.1:8050/`.

Here is the updated content in a clean, professional **README.md** format. I have structured it to include the installation steps, project context, and execution instructions.

---

# Automobile Sales Statistics Dashboard

This project is an interactive data visualization dashboard built using **Dash** and **Plotly**. It analyzes historical automobile sales data, specifically comparing performance during recessionary and non-recessionary periods.

## Getting Started

### Prerequisites

Ensure you have **Python 3.8** installed on your system.

### How to Install Dependencies

To set up the environment, run the following commands in your terminal to install the required libraries:

1. **Install Setup Tools:**
```bash
pip3.8 install setuptools

```


2. **Install Packaging:**
```bash
python3.8 -m pip install packaging

```


3. **Install Core Dashboard Libraries (Pandas & Dash):**
```bash
python3.8 -m pip install pandas dash

```


4. **Install Additional Itertools:**
```bash
pip install more-itertools

```



---

## Project Structure

* **`DV0101EN-Final-Assign-Part1-v1.ipynb`**: Jupyter Notebook containing the initial data exploration and static visualizations using Matplotlib and Seaborn.
* **`DV0101EN-Final-Assign-Part-2-Questions.py`**: The main Python script that launches the interactive Dash web application.

---

## Running the Application

Once the dependencies are installed, you can launch the dashboard by running the following command in your terminal:

```bash
python3.8 DV0101EN-Final-Assign-Part-2-Questions.py

```

After running the command, open your web browser and navigate to the local address provided (typically `http://127.0.0.1:8050/`).

## Dashboard Features

* **Recession Period Statistics:** View line charts for average sales, pie charts for expenditure share by vehicle type, and bar charts for sales by vehicle type during recessions.
* **Yearly Statistics:** Select a specific year to view total monthly sales, average vehicle sales by type, and advertisement expenditure distribution.

## Authors

* Dr. Pooja 


* Alison Woolford

## 📜 License

© 2020 IBM Corporation — All Rights Reserved.
  This project is from IBM