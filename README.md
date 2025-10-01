

## **Project Title**

Exploratory Data Analysis (EDA) on COVID-19 Global Cases Dataset

---

## **Objective**

The main objective of this project is to perform **exploratory data analysis (EDA)** on the COVID-19 dataset to:

* Understand global trends and patterns of COVID-19 cases and deaths.
* Identify the most affected countries.
* Visualize the data using plots for better understanding.

---

## **Dataset Description**

The dataset is sourced from **Our World in Data (OWID)** and contains the following columns:

* `date`: Reporting date
* `location`: Country or region
* `total_cases`: Cumulative confirmed COVID-19 cases
* `total_deaths`: Cumulative COVID-19 deaths

> Note: The dataset does not include total recovered cases.

---

## **Tools & Libraries Used**

* **Python**
* **Jupyter Notebook / Google Colab**
* **Libraries**: `pandas`, `matplotlib`, `seaborn`

---

## **Project Steps**

1. **Import Libraries and Dataset** – Load the CSV file and check the top rows.
2. **Data Cleaning** – Removed duplicates and checked for null values.
3. **Exploratory Data Analysis (EDA)** –

   * Show top 5 rows.
   * Generate summary statistics.
   * Count the number of countries in the dataset.
   * Identify top 10 most affected countries.
4. **Visualization** –

   * Line chart: Global confirmed cases over time.
   * Bar chart: Top 10 countries with highest deaths.
   * Pie chart: Global survivors vs deaths.
5. **Observations and Conclusion** – Summarize key insights from the data.

---

## **Observations**

* Global confirmed cases increased sharply during multiple waves of COVID-19.
* Countries like **United States, India, and Brazil** recorded the highest confirmed cases and deaths.
* The majority of infected people survived globally.
* Deaths, though a small percentage of total cases, represent a significant number worldwide.

---

## **Conclusion**

* COVID-19 spread rapidly worldwide, with multiple waves reflected in global case trends.
* A small set of countries contributed a large share of total cases and deaths.
* Most patients survived, but the **global death toll remains significant**.
* Missing recovery data highlights inconsistencies in reporting across countries.

---

## **Instructions to Run the Project**

1. Clone or download the repository.
2. Open the **Jupyter Notebook (.ipynb)** in Jupyter or Google Colab.
3. Run all cells sequentially to generate outputs and visualizations.

---
