📊 Country GDP ETL Pipeline
📌 Overview

This project implements an ETL (Extract, Transform, Load) pipeline to collect and process country GDP data from a web source and store it for analysis.

⚙️ Features
Web scraping using BeautifulSoup
Data cleaning and transformation with Pandas
Conversion of GDP values from millions to billions
Storage in CSV and SQLite database
SQL querying for analysis
Logging of pipeline execution
🛠️ Tech Stack
Python
Pandas, NumPy
BeautifulSoup, Requests
SQLite
🔄 ETL Workflow
Extract: Scrape GDP data from a Wikipedia archive
Transform:
Clean numeric values
Convert data types
Standardize units
Load:
Save as CSV
Store in SQLite database
Query:
Retrieve countries with GDP ≥ $100B
