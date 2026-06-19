# 🏙️ Urban Mobility & Economy Analysis 2024

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AeRWISu0kwJPH94dVlmNUQ9JW3WEbvy_)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/wasuarezm-cell/ladb_mobility_economy_2024)

## ✔️ What is this project about?
This project evaluates how urban mobility impacts economic productivity across major cities worldwide in 2024. 

Using real-world data from the **TomTom Traffic Index** and **OECD Cities**, the analysis focuses on cleaning, merging, and exploring key metrics such as traffic congestion levels (`jams_delay`) and GDP per capita (`city_gdp_capita`). The goal is to identify patterns and determine where strategic investments in transportation infrastructure are most critical to boosting economic productivity in emerging global megalopolises.

## 📁 What does this repository contain?
* **`S5 ladb_mobility_economy_project_student.ipynb`**: The main Jupyter Notebook containing the full Python pipeline. It covers data cleaning, column standardization, filtering for 2024, and calculating average traffic delays per city.
* **Data Visualizations**: Built-in charts generated with `seaborn` and `matplotlib` (including boxplots and histograms) that illustrate the distribution of traffic and its correlation with economic indicators.

## 🚀 How to open the notebook in Colab?
You can easily explore the code, view the charts, and interact with the analysis right in your browser without installing anything locally:

👉 **[Click here to open the Notebook in Google Colab](https://colab.research.google.com/drive/1AeRWISu0kwJPH94dVlmNUQ9JW3WEbvy_)**

## ⚙️ How to reproduce this analysis?
If you want to run the analysis from scratch or fork the project, follow these steps:

1. **Open the Notebook**: Launch `S5 ladb_mobility_economy_project_student.ipynb` in Colab using the badge above, or clone this repository to run it locally.
2. **Load the Datasets**: The data loading process is programmed in "Step 1" using `pandas`. It relies on the paths `/datasets/tomtom_traffic.csv` and `/datasets/oecd_city_economy.csv`. If running locally, ensure these CSV files are placed inside a `datasets/` folder in your working directory.
3. **Run Sequentially**: Execute the cells from top to bottom. The notebook logically flows through:
   * Data exploration and standardization (formatting to *snake_case* and cleaning data types).
   * Filtering the dataset specifically for the year 2024.
   * Aggregating traffic delay averages by city.
   * Merging (*inner join*) the mobility and economy datasets.
   * Generating the final visualizations and insights.
