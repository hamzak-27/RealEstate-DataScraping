# RealEstate-DataScraping

This project is a Python-based real estate data scraping tool that fetches property listings and details from Zillow using the ScrapeAK API. The script retrieves real estate data such as addresses, prices, property types, and other essential attributes, which are then processed and saved into a CSV file for further analysis.

**Features:**
- Fetches property listings based on a specified location URL.
- Retrieves detailed property information using Zillow's unique property ID (ZPID).
- Extracts key property attributes such as price, location, bedrooms, bathrooms, and lot area.
- Cleans and processes data into a structured pandas DataFrame.
- Exports the final cleaned data into a CSV file.

**Requirements:**
- Python 3.x
- requests, numpy, pandas, beautifulsoup4

**Usage:**
- Set your ScrapeAK API key.
- Define the Zillow listing URL for the desired location.
- Run the script to fetch, process, and save the real estate data.
