Urban Mobility and Economy Analysis 2024
✔ What is this project about?
This project evaluates how urban mobility relates to economic productivity in major global cities during 2024 (covering multiple countries worldwide, not just Latin America).

By processing real-world data from the TomTom Traffic Index and OECD Cities, the analysis focuses on cleaning, merging, and analyzing key metrics such as traffic congestion levels (jams_delay) and GDP per capita (city_gdp_capita). The ultimate goal is to identify patterns that help determine in which cities and emerging megalopolises it is most critical and strategic to invest in transportation infrastructure to boost economic productivity.

✔ What does this repository contain?
S5 ladb_mobility_economy_project_student.ipynb: This is the main notebook of the project. It contains all the Python code used for data cleaning, column standardization, filtering for the year 2024, and calculating average traffic delays per city.

Data Visualizations: The notebook includes charts generated with seaborn and matplotlib (such as boxplots and histograms) that allow observing the distribution of traffic and its direct relationship with economic indicators.

✔ How to open the notebook in Colab?
You can explore the code, view the charts, and run the analysis without installing anything on your computer by clicking the link below:

👉 Open Notebook in Google Colab

✔ How to reproduce this analysis?
To run the analysis from scratch and get the same results, follow these steps:

Open the main file: Launch the S5 ladb_mobility_economy_project_student.ipynb notebook in Google Colab using the link above, or clone it to use in your local Jupyter environment.

Load the Datasets: Data loading is programmed directly in "Step 1" of the notebook using pandas. It uses the internal paths /datasets/tomtom_traffic.csv and /datasets/oecd_city_economy.csv. If you are running this locally, make sure to have the CSV files located in a datasets folder in the same directory as your environment.

Sequential Execution: Run the cells in descending order. The notebook is designed to follow a logical flow:

Data exploration and standardization (renaming to snake_case and cleaning numeric/date formats).

Filtering exclusively for the year 2024.

Grouping data to obtain average traffic times per city.

Merging (inner join) the mobility and economy tables.

Executing the visualization cells to view the resulting charts.
