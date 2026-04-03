# Indian Crime Data Analysis Project

##  Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on an Indian crime dataset to uncover patterns, trends, and insights across cities, crime types, and time. The goal is to transform raw data into meaningful insights using data cleaning, visualization, and SQL-based analysis.

---
## Tableau Dashboard

View Dashboard: https://public.tableau.com/app/profile/palak.5572/viz/Book1_17749757710730/Dashboard2?publish=yes

---

##  Objectives

* Analyze crime distribution across cities and states
* Identify trends over years and peak crime periods
* Study victim demographics (age, gender)
* Evaluate arrest rates and law enforcement effectiveness
* Generate actionable insights from data

---

## Tech Stack

* **Python** (Pandas, NumPy)
* **Data Visualization**: Matplotlib, Seaborn
* **Database**: SQLite
* **Environment**: Jupyter Notebook / Google Colab

---

## Workflow

### 1. Data Collection

* Dataset loaded from a public GitHub source

### 2. Data Cleaning

* Removed duplicates
* Handled missing values
* Fixed invalid entries (age, latitude, longitude)
* Standardized categorical values

### 3. Feature Engineering

* Extracted `hour` and `day_of_week` from date
* Created `age_group` categories
* Derived `law_type` and `ipc_final` from IPC sections

### 4. Exploratory Data Analysis (EDA)

* Crime distribution by type
* City and state-wise crime comparison
* Yearly crime trends
* Heatmaps for time-based patterns
* Gender and age-based crime analysis
* Arrest rate evaluation

### 5. SQL Analysis

* Stored cleaned data in SQLite database
* Performed queries for:

  * Top cities with highest crime
  * Most common crimes
  * Year-wise trends
  * Arrest rates by crime type
  * Peak crime hours and days

---

## Key Insights

* **Most Dangerous City:** Mumbai
* **Most Common Crime:** Theft
* **Peak Crime Hour:** Midnight (00:00)
* **Most Affected Gender:** Male
* **Average Victim Age:** ~42 years
* **Overall Arrest Rate:** ~21.9%
* **Safest City:** Guwahati

---

## Sample Visualizations

* Bar charts for crime distribution
* Line plots for yearly trends
* Heatmaps for time-based crime patterns
* Comparative charts for arrest rates

---

##  Project Structure

```
 Crime-Data-Analysis
│── Crime.ipynb          # Main notebook
│── crime.db             # SQLite database
│── README.md            # Project documentation
```

---

##  How to Run

1. Clone the repository
2. Open the notebook in Jupyter/Colab
3. Run all cells step-by-step
4. Explore visualizations and SQL queries

---


##  Future Improvements

* Add interactive dashboards (Plotly / Power BI)
* Build predictive models for crime forecasting
* Deploy as a web-based analytics dashboard
* Integrate real-time crime data APIs

---

##  Conclusion

This project demonstrates strong skills in data cleaning, EDA, visualization, and SQL integration. It provides meaningful insights into crime patterns and showcases the ability to turn raw data into impactful stories.

