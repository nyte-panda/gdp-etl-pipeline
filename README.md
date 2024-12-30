# ETL Pipeline for GDP Data Extraction and Transformation

## Project Overview
This project demonstrates the creation of an ETL (Extract, Transform, Load) pipeline for accessing, processing, and storing data about the GDP of countries in USD billions. The data is scraped from a Wikipedia page, transformed, and loaded into both a CSV file and a SQLite database. The pipeline also logs the process with timestamps to a log file.

## Objective
The goal of this project is to automate the extraction of the list of countries ordered by their GDP in nominal terms (in USD). The data is scraped from the International Monetary Fund (IMF) report available on Wikipedia. The extracted data is processed and transformed, then saved into two formats: 
1. A CSV file (`Countries_by_GDP.csv`).
2. A database file (`World_Economies.db`) containing a table with country names and their GDPs.

## Technologies Used
- Python
- Requests
- BeautifulSoup (for web scraping)
- SQLite (for the database)
- CSV (for storing data in CSV format)
- Logging (for tracking the progress of the ETL process)

## Project Requirements
Before running the project, you need to install the following Python packages:

```bash
pip install requests beautifulsoup4 sqlite3

