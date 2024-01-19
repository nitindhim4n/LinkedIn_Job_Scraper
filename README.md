# LinkedIn Job Scraper

## Overview
This Python project is designed to scrape job listings from LinkedIn, providing a versatile tool for gathering extensive datasets. The script utilizes the Selenium library for web scraping and incorporates data cleaning techniques. The goal is to extract relevant information such as company name, job title, location, and post URLs from job listings on the LinkedIn platform.

## Key Features
- **Dynamic Scraping:** The script employs Selenium to dynamically scrape job listings, allowing for flexibility and adaptability to changes on the LinkedIn website.
- **Filtering:** Applied filters for full-time, contract positions, and remote work, ensuring the dataset is refined to specific job types.
- **Infinite Scrolling:** Utilizes infinite scrolling to continuously load job listings, ensuring a comprehensive dataset is gathered.

## Data Cleaning and Refinement
- **Extraction:** Extracted pertinent details from job listings, including company name, job title, location, and post URLs.
- **Location Filtering:** Removed job listings located in the United States and Canada for a worldwide focus.

## Google Sheets Integration
- **Connection with Google Sheets:** Established a connection with Google Sheets using gspread and df2gspread libraries.
- **Export to Google Sheets:** Exported the cleaned dataset to Google Sheets for efficient collaboration and further analysis.

## Requirements
- Python
- Selenium
- Pandas
- gspread
- df2gspread
- ChromeDriver

## Usage
1. Install the required dependencies using `pip install -r requirements.txt`.
2. Update the `driver_path` variable in the script with the correct path to your ChromeDriver executable.
3. Run the script to start scraping LinkedIn job listings.

## Disclaimer
This project is for educational and personal use only. Be mindful of LinkedIn's terms of service and use this tool responsibly.

Feel free to contribute, report issues, or suggest enhancements. Happy job scraping!
