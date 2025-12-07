# E-Commerce Search Analytics Dashboard
## Datase : https://drive.google.com/file/d/12r1l-nMxtqsvDUamhZo2tUPH-eifqCVC/view?usp=drive_link
## Cleaned CSV : https://drive.google.com/file/d/18JRC5Ow90DTDPpMHifKG2TGLW1saGFJf/view?usp=drive_link
## Project Overview
This project analyzes e-commerce search behavior to understand how users interact with an online store during product searches. The goal is to identify search performance issues, demand trends, and user preferences that impact product discovery and business decisions.


## Objectives
- Analyze total search activity
- Identify zero and low result searches
- Measure search failure rate
- Track weekly search trends
- Identify top search keywords
- Analyze category and brand demand
- Study user price and rating preferences

## Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- Microsoft Excel

## Dataset Description
The dataset contains real-world style e-commerce search log data with fields such as:
- Search ID
- Search Keyword
- Brand
- Category
- Price Filters
- Rating Filters
- Total Results
- Search Date

## Data Cleaning Steps
- Removed records with missing search keywords
- Standardized column names
- Converted date fields to datetime format
- Created weekly time buckets
- Converted price and rating fields to numeric
- Labeled missing brand and category values as "Unknown"
- Created derived columns for price segment and rating segment

## Key KPIs
- Total Searches
- Zero Result Searches
- Low Result Searches
- Search Fail Rate (%)
- Weekly Search Trend
- Top Search Keywords
- Category Demand
- Brand Demand
- Price Intent Distribution
- Rating Preference Distribution

## Dashboard Design
The dashboard is built in Power BI with a two-page layout:
- Page 1: Search Performance Overview (KPIs, trends, demand)
- Page 2: User Preferences (Price and Rating analysis)

## Key Insights
- A high percentage of searches fail due to zero or very low results
- Mid-budget products dominate user interest
- Users strongly prefer well-rated products
- Skincare-related categories and brands show high demand
- Seasonal spikes observed in search activity

## Business Recommendations
- Improve search relevance and reduce zero-result searches
- Expand product coverage for high-demand keywords
- Promote mid-budget and high-rated products
- Use trending keywords for demand forecasting

## Files Included
- Power BI Dashboard (.pbix)
- Technical Documentation (PDF)
- Python Notebook for Data Cleaning & Analysis

## Author
Vimal
