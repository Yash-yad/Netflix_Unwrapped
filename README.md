# Netflix Unwrapped

## Project Overview
**Netflix Unwrapped** is a data analytics project that explores the Netflix dataset sourced from Kaggle. The project focuses on cleaning, transforming, and analyzing Netflix’s extensive content catalog to uncover trends, patterns, and insights related to movies and TV shows.


## Project Tasks
This project covers the following key analytics tasks:

- **Data Cleaning and Handling Missing Values**  
  Filling missing entries in director, cast, and country columns with appropriate values.

- **Feature Engineering**  
  Creating new columns such as:
  - `year_added` and `month_added` (from the date content was added)  
  - `is_movie` (binary flag for Movies vs TV Shows)  
  - `duration_int` and `duration_type` (numeric and categorical parts of content duration)  
  Also dropping irrelevant columns like `show_id`.

- **Ensuring Data Integrity and Consistency**  
  Handling missing values and consistent data types for accurate analysis.

- **Summary Statistics and Insights**  
  Generating descriptive statistics for numeric columns and summarizing distributions of content types and countries.

- **Identifying Patterns and Trends**  
  Using visualizations to explore:
  - Content added per year  
  - Distribution of Movies vs TV Shows over release years  
  - Genre expansion and frequency

- **Handling Outliers and Data Transformations**  
  (To be included in further stages)

- **Initial Visual Representations**  
  Utilizing Seaborn and Matplotlib for clear and insightful plots.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## How to Run
1. Clone the repository or download the `netflix_titles.csv` dataset 
2. Open the Jupyter Notebook provided.
3. Run cells sequentially to perform data cleaning, feature engineering, and visualization.
4. Modify or extend analysis as needed.

## Insights & Findings
- Netflix’s content library has grown significantly over the years.
- Movies and TV Shows show distinct trends in release years.
- Genre distribution is diverse, with some genres appearing more frequently.
- The duration of content varies significantly between movies and TV shows.

---



## 📊 Power BI Dashboard

![Netflix Dashboard](4f2f7076-017b-4008-95f1-9904a72b303b.png)

### Dashboard Highlights:
This interactive dashboard created in Power BI visually represents the cleaned Netflix dataset and offers insightful views such as:

- **KPI Cards**
  - **Total Number of Movies:** `6038`
  - **Total Hours of Content:** `8714`

- **Interactive Filters**
  - A slider to filter by **Release Year** ranging from `1925` to `2021`.

- **Visualizations**
  - **Bar Chart:** Shows amount of content based on rating categories, split between Movies and TV Shows.
  - **World Map:** Geographic distribution of content across different countries.
  - **Line Chart:** Relationship between number of movies and their duration.
  - **Pie Chart:** Comparison of total count of Movies (69.3%) vs TV Shows (30.7%).
  - **Line Graph:** Content added per year, revealing growth over time.

- **Dark Theme Design** for better contrast and modern aesthetics.

---

## Project Tasks

This project covers the following key analytics tasks:

- **Data Cleaning and Handling Missing Values**  
  Filling missing entries in director, cast, and country columns with appropriate values.

- **Feature Engineering**  
  Creating new columns such as:
  - `year_added` and `month_added` (from the date content was added)  
  - `is_movie` (binary flag for Movies vs TV Shows)  
  - `duration_int` and `duration_type` (numeric and categorical parts of content duration)  
  Also dropping irrelevant columns like `show_id`.

- **Ensuring Data Integrity and Consistency**  
  Handling missing values and consistent data types for accurate analysis.

- **Summary Statistics and Insights**  
  Generating descriptive statistics for numeric columns and summarizing distributions of content types and countries.

- **Identifying Patterns and Trends**  
  Using visualizations to explore:
  - Content added per year  
  - Distribution of Movies vs TV Shows over release years  
  - Genre expansion and frequency

- **Handling Outliers and Data Transformations**  
  (To be included in further stages)

- **Initial Visual Representations**  
  Utilizing Seaborn and Matplotlib for clear and insightful plots.

---

## 🛠️ Libraries Used

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

---

## 🔧 How to Run

1. Clone the repository or download the `netflix_titles.csv` dataset.
2. Open the Jupyter Notebook provided.
3. Run cells sequentially to perform data cleaning, feature engineering, and visualization.
4. Modify or extend analysis as needed.

---

## 🔍 Insights & Findings

- Netflix’s content library has grown significantly over the years.
- Movies and TV Shows show distinct trends in release years.
- Genre distribution is diverse, with some genres appearing more frequently.
- The duration of content varies significantly between movies and TV shows.

---

> 📬 *Feel free to contribute or raise issues for improvements!*

---

*Created by Yash Yadav*


