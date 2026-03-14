# COVID-19 Country Wise Data Analysis

## Project Description

This project performs exploratory data analysis (EDA) and visualization on a global COVID-19 dataset.
The goal of this project is to analyze country-wise pandemic statistics and identify important patterns in confirmed cases, deaths, recoveries, and weekly changes.

Using Python data analysis libraries, the dataset is cleaned, analyzed, and visualized to better understand the global impact of COVID-19 across different countries and WHO regions.

---

## Objectives

The main objectives of this project are:

* Understand the structure of the COVID-19 dataset
* Perform data cleaning and preprocessing
* Analyze country-wise COVID-19 statistics
* Identify the most affected countries
* Study recovery and death rates
* Analyze weekly growth trends
* Visualize patterns using charts and graphs

---

## Dataset Information

The dataset used in this project contains **country-wise COVID-19 statistics**.

### Dataset Features

The dataset includes the following columns:

| Column                 | Description                                  |
| ---------------------- | -------------------------------------------- |
| Country/Region         | Name of the country                          |
| Confirmed              | Total confirmed COVID-19 cases               |
| Deaths                 | Total number of deaths                       |
| Recovered              | Total recovered cases                        |
| Active                 | Currently active cases                       |
| New cases              | Newly reported cases                         |
| New deaths             | Newly reported deaths                        |
| New recovered          | Newly recovered patients                     |
| Deaths / 100 Cases     | Death rate per 100 confirmed cases           |
| Recovered / 100 Cases  | Recovery rate per 100 confirmed cases        |
| Deaths / 100 Recovered | Death rate among recovered patients          |
| Confirmed last week    | Total confirmed cases in the previous week   |
| 1 week change          | Change in confirmed cases during the week    |
| 1 week % increase      | Percentage increase in cases during the week |
| WHO Region             | World Health Organization region             |

The dataset contains **187 countries and multiple statistical indicators** related to COVID-19.

---

## Technologies Used

The project is implemented using the following tools and libraries:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

These tools help in data manipulation, statistical analysis, and visualization.

---

## Project Workflow

The project follows a structured data analysis workflow:

### 1. Data Loading

The dataset is imported into Python using the Pandas library.

### 2. Data Exploration

Basic information about the dataset is explored including:

* dataset shape
* column names
* statistical summary
* data types

### 3. Data Cleaning

Missing values are checked and handled to ensure the dataset is suitable for analysis.

### 4. Data Analysis

Multiple analyses are performed including:

* Top countries by confirmed cases
* Countries with highest deaths
* Countries with highest recoveries
* Region-wise COVID-19 statistics
* Weekly case growth analysis
* Global COVID-19 statistics

### 5. Data Visualization

Several visualizations are created to better understand the data:

* Bar charts for top affected countries
* Pie charts for WHO region distribution
* Scatter plots for confirmed vs deaths
* Correlation heatmaps between variables

---

