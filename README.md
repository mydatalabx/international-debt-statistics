# International Debt Statistics Analysis

SQL-based analysis of international debt data collected by The World Bank to identify patterns in debt across developing countries and answer key questions about global debt distribution.

## Overview
This project analyzes international debt data to understand how developing countries manage their economies through debt. The analysis examines debt across multiple categories and identifies countries with the highest debt burdens and lowest repayment rates.

## Research Questions
- What is the number of distinct countries present in the database?
- What country has the highest amount of debt?
- What country has the lowest amount of principal repayments?

## Technologies Used
- SQL (PostgreSQL)
- Jupyter Notebook
- Database querying and analysis

## Dataset
The World Bank's international debt data containing:
- Country names and codes
- Debt indicator descriptions and codes
- Debt values in current US dollars
- Multiple debt categories (infrastructure, principal repayments, etc.)

## Key Analysis
- Counted distinct countries in the debt database
- Identified the country with the highest total debt
- Found the country with the lowest principal repayments (indicator code: DT.AMT.DLXF.CD)
- Analyzed debt patterns across developing nations

## SQL Queries
Three main queries were developed:
1. `num_distinct_countries` - Count of unique countries
2. `highest_debt_country` - Country with maximum debt
3. `lowest_principal_repayment` - Country with minimum repayments

## Files
- `notebook.ipynb` - SQL queries and analysis
- `images/` - Query results and visualizations

## Context
Countries take on debt to manage their economies and fund infrastructure spending necessary for citizens' quality of life. This analysis helps understand global debt patterns in developing nations.

## Project Source
Completed as part of DataCamp's SQL curriculum.
