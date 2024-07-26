# Bio-Fertilizer Web Scraper

## Project Overview

This project consists of a Python script designed to scrape data about bio-fertilizers from 'Trade India'. This is a personal exploration into the realm of web scraping. The aim is to understand how to extract data from web pages using Python libraries such as `requests` and `BeautifulSoup`.

## How It Works

The script operates by sending HTTP requests to the target URL and parsing the returned HTML content. Specific details about various bio-fertilizers are extracted, such as product name, price, rating, company, contact name, and address. These details are then compiled into a structured dataset and exported as a CSV file.

### Components

1. **Fetching Web Pages**: Uses `requests` to make HTTP requests and retrieve web pages.
2. **HTML Parsing**: Utilizes `BeautifulSoup` to parse HTML and extract data.
3. **Data Handling**: Structures the scraped data using `pandas` and outputs to CSV format.

## Development Environment

- **Language**: Python
- **External Libraries**: `requests`, `BeautifulSoup4`, `pandas`
- **Platform**: Developed and tested under macOS, compatible with any OS where Python can be run.

## Notes

This is a basic implementation of web scraping aimed at educational purposes. This script is configured for a specific website and structured to handle its HTML layout as of the last testing date. For other websites or future changes in the website layout, the script may require adjustments.
