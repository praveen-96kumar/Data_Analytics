# End-to-End Bike Share Data Analysis Project (2024)

This project is an end-to-end data analysis workflow demonstrating how to use SQL and Power BI to analyze a bike share dataset to answer a key business question about pricing and profitability.

---

## Project Overview

You will act as a Data Analyst helping Toman Bike Share understand if increasing prices next year is feasible based on historical bike share data from 2021 and 2022.

The project covers:
- Setting up a SQL database and importing raw data
- Developing key SQL queries to calculate revenue, profit, and trends
- Connecting SQL data to Power BI for visualization
- Building an interactive Power BI dashboard
- Making data-driven price increase recommendations

---

## Data

Raw data files for bike share usage and cost information are included in the [`file/`] folder as CSV files.

---

## SQL Scripts

The pbix file contains scripts for:
- Creating the necessary database schema and tables (`create_tables.sql`)
- Importing raw data into SQL tables (`import_data.sql`)
- Running analysis queries that calculate revenue, profit, and other KPIs (`analysis_queries.sql`)

---

## Power BI Dashboard

The Power BI dashboard file [`powerbi/BikeShare_Dashboard.pbix`](https://github.com/praveen-96kumar/Data_Analytics/blob/main/DashBoard.png) connects to the SQL database and visualizes key performance metrics such as:

- Hourly revenue analysis
- Profit and revenue trends over time
- Seasonal revenue patterns
- Rider demographics

---

## Getting Started

1. **Set up SQL Server:**
   - Install Microsoft SQL Server Express and SQL Server Management Studio (SSMS).
   - Run the scripts in the `sql/` folder to create the database, tables, and import data.

2. **Run Analysis Queries:**
   - Execute the SQL queries to generate the analysis results.

3. **Connect Power BI:**
   - Open the Power BI Desktop project file.
   - Connect to your local SQL Server instance.
   - Refresh data to visualize current query results.

4. **Explore the Dashboard:**
   - Use slicers and visuals to explore key insights.

---

## Key Insights

- Price was increased by 25% between 2021 and 2022.
- Customer demand increased by around 64% despite price increase.
- Revenue and profit both showed significant growth.
- This suggests there's room for a price increase next year.

