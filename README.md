# CMSC408-SP2025-HW8

## Homework 8 - World Bank Indicator Analysis

This project was completed as part of CMSC 408 (Databases and Data Analytics) at VCU in Spring 2025.

In this assignment, we worked with World Bank Development Indicator (WDI) data to practice large-scale SQL querying, data analysis, and report generation.

The main goals were:

- Explore the WDI database structure.
- Clean and filter country-level data.
- Perform aggregations by region and income group.
- Identify missing data and perform data corrections.
- Generate percentage breakdowns and pivot tables using SQL.
- Document results clearly in a Quarto report (`report.qmd` → `report.html`).

## Project Structure

- `report.qmd` — Quarto file containing all SQL queries, outputs, and analysis.
- `report.html` — Rendered final report.
- `.env` — Environment variables for database connection (not included in repo).
- `helpers.py` — Utility functions for connecting to the database and executing SQL.
- `README.md` — Project documentation (this file).

## How to Run

1. Set up your environment:
   - Install Python 3, Pandas, SQLAlchemy, and required libraries.
   - Install Quarto CLI.
   - Configure a valid `.env` file with your MySQL credentials.

2. Render the report:
   ```bash
   quarto render report.qmd
