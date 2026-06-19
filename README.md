# 🏙️ Urban Mobility & Economy Analysis 2024

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AeRWISu0kwJPH94dVlmNUQ9JW3WEbvy_)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/wasuarezm-cell/ladb_mobility_economy_2024)

This repository contains the analysis evaluating how urban mobility impacts economic productivity across major cities worldwide in 2024. 

The project uses real-world data from the **TomTom Traffic Index** and **OECD Cities**, focusing on cleaning, merging, and exploring key metrics such as traffic congestion levels (`jams_delay`) and GDP per capita (`city_gdp_capita`).

## 📂 Repository Contents

- `S5 ladb_mobility_economy_project_student.ipynb`
  → Main notebook containing the full Python pipeline: data cleaning, EDA, distributions, column standardization, and final conclusions.

## ▶ How to open the notebook in Google Colab

Click the button below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AeRWISu0kwJPH94dVlmNUQ9JW3WEbvy_)

Or:
1. Open the `.ipynb` file directly on GitHub.
2. Click on the **Open in Colab** button at the top of the file viewer.

## 📘 How to reproduce the analysis

1. Open `S5 ladb_mobility_economy_project_student.ipynb`.
2. Run the cells in sequential order.
3. The notebook relies on datasets located at `/datasets/tomtom_traffic.csv` and `/datasets/oecd_city_economy.csv`. *(Note: If running locally, ensure these files are placed inside a `datasets/` folder in your working directory).*

## 🧠 Analysis Objective

- Process and merge datasets using a reproducible data cleaning pipeline (handling data types and snake_case formatting).
- Analyze behaviors, distributions, and outliers using Python visualizations (`seaborn` and `matplotlib`).
- Identify patterns between urban traffic congestion and economic performance.
- Generate insights to determine where strategic investments in transportation infrastructure are most critical to boosting economic productivity in emerging global megalopolises.

```
