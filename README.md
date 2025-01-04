# WEB-SCRAPING

# Amazon Product Scraper

This project scrapes product data from Amazon for a specified search query. The scraper extracts details such as product title, price, rating, reviews, availability status, and product description. The scraped data is then saved to a CSV file (`amazon_data.csv`).

## Features

- Scrapes product title, price, rating, reviews, availability, and description.
- Saves the scraped data to a CSV file (`amazon_data.csv`).
- Scrapes multiple pages of products based on a search query (e.g., "Playstation 4").

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `pandas` library
- `numpy` library

To install the required libraries, run the following command:

```bash
pip install requests beautifulsoup4 pandas numpy



# Notes
Scraping Amazon may be subject to Amazon's policies and terms of service.
Use a valid User-Agent to avoid being blocked.
Be respectful when scraping data and avoid overwhelming Amazon's servers.
