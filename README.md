# 📊 Country GDP ETL Pipeline

## 🚀 Overview
This project implements an **ETL (Extract, Transform, Load) pipeline** in Python to collect, process, and store country GDP data from a web source.

The pipeline extracts raw GDP data, transforms it into a clean and standardized format, and loads it into both a CSV file and a SQLite database for further analysis.

---

## ⚙️ Features
- 🌐 Web scraping using BeautifulSoup and Requests  
- 🧹 Data cleaning and transformation using Pandas and NumPy  
- 🔄 Conversion of GDP values from **millions to billions**  
- 💾 Data storage in CSV and SQLite database  
- 🔍 SQL querying for analysis  
- 📝 Logging of ETL pipeline execution  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- BeautifulSoup  
- Requests  
- SQLite  

---

## 🔄 ETL Workflow

### 1. Extract
- Scrapes GDP data from a Wikipedia archive page  
- Parses HTML using BeautifulSoup  

### 2. Transform
- Cleans numeric values (removes commas)  
- Converts data types (string → float)  
- Converts GDP from millions to billions  
- Rounds values for consistency  

### 3. Load
- Saves processed data to a CSV file  
- Loads data into SQLite database  

### 4. Query
- Runs SQL queries to analyze data  
- Example: Filter countries with GDP ≥ $100B  

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/ananthuswethanya-art/country-gdp-etl-.git
cd country-gdp-etl-
