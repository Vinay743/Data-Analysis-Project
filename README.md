# Data-Analysis-Project

📊 ICT Indicators Analysis & Power BI Dashboard

This project analyzes ICT (Information & Communication Technology) indicators across major Indian cities and visualizes key insights using Python libraries, SQLite, and an interactive Power BI Dashboard.

The repository contains the complete workflow — raw dataset, data cleaning notebook, SQL database, and the final Power BI report.

📁 Project Structure
File	Description
ICT_Subdimension_Dataset new.csv- Primary dataset containing ICT indicators such as broadband coverage, internet access, e-government metrics, etc.
New ICT.db- SQLite database generated for structured querying and analysis.
project.ipynb- Jupyter Notebook performing data loading, cleaning, transformation, and data visualization.
Dashboard.pbix- Power BI dashboard visualizing sub-dimensions of ICT and ranking cities.

📊 Dataset Overview

The dataset includes ICT-related metrics for major Indian cities:

Household Internet Access (%)

Fixed Broadband Subscriptions (%)

4G Wireless Coverage (%)

E-Government (%)

Z-score Standardized Indicators

🧠 Data Processing (project.ipynb)

The notebook includes:

Importing and inspecting dataset

Cleaning missing values

Standardizing indicators using z-score

Exporting cleaned data into SQLite database

Preparing structured results for Power BI

🗄️ SQLite Database (New ICT.db)

Contains structured tables created from the cleaned dataset.

📊 Dashboard Overview

This Power BI dashboard provides a visual analysis of key ICT indicators across Indian cities. It highlights overall digital readiness and allows users to compare cities across multiple ICT dimensions.

🔍 Key Insights Displayed

Average Internet Access across cities

Average Smart Electricity Meter Adoption

Highest 4G Wireless Coverage

Lowest e-Government Score

📈 Visual Components

Top 10 Cities by 4G Broadband Coverage

Top 10 Cities by Household Internet Access (trend over years)

Interactive Map showing ICT distribution across India

City Filter Panel to analyze each city individually

This dashboard helps identify top-performing regions, track digital infrastructure growth, and understand gaps in ICT access and governance.
