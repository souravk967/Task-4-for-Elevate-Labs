🚀 SQL Data Analysis & Visualization Project

This repository contains SQL queries and data visualizations that demonstrate data extraction, transformation, and analysis from a SQLite database. The project includes use cases such as identifying maximum payloads, filtering launch site data, and analyzing automobile sales trends using bubble plots.


💾 Dataset

The project uses a SQLite database  which contains launch records, booster versions, payload mass, launch sites, customer details, and automobile sales data (for visualization).

📊 Key Feature

1. 🚀 SpaceX Launch Data Analysis

Find Booster Versions with Max Payload
SQL query uses a subquery to extract all booster versions that carried the maximum payload mass.

Filter Launches by Site
Retrieves the first 5 records where launch sites begin with 'CCA', using the LIKE operator.

2. 📈 Automobile Sales Trend Analysis

A Bubble Plot was developed using Python to visualize how seasonality affects monthly automobile sales.

Bubble size represents Seasonality Weight for each month.

Focused on non-recession years for clarity in understanding natural market trends.

📌 How to Run

Clone the repo:

git clone [https://github.com/your-username/sql-data-analysis-project.git](https://github.com/souravk967/Task-4-for-Elevate-Labs)
cd sql-data-analysis-project


Open the SQL files using a Jupyter Notebook or a SQL editor that supports %sql magic (e.g., Jupyter with ipython-sql).

To view the bubble plot:

Open automobile_sales_bubble_plot.ipynb in Jupyter Notebook or any Python IDE.

Ensure you have the required packages installed:

pip install matplotlib pandas


🧰 Tools & Technologies

SQLite (for relational data storage)

SQL (for data querying)

Python & Matplotlib (for data visualization)

Jupyter Notebook (for interactive coding)

📷 Screenshots
SQL Query	Visualization

	


🙌 Acknowledgments

SpaceX Launch Data

Automobile Sales Dataset

Jupyter & SQLite for seamless integration
