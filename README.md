# Flipkart Mobile Scraper

## Description
A Python-based web scraper that extracts mobile phone details under ₹10,000 from Flipkart using Selenium. The tool automates the search process, navigates through pages, and stores the phone name, price, and rating in a CSV file for further analysis.

## Features
- **Web Scraping**: Collects mobile phone names, prices, and ratings.
- **Automated Navigation**: Clicks through Flipkart's search results to collect data across multiple pages.
- **CSV Export**: Saves the extracted data into a CSV file for easy access and analysis.

## Technologies Used
- **Python**: The programming language used for implementing the scraper.
- **Selenium**: A library for web automation, used for interacting with the Flipkart website.
- **CSV**: For exporting the scraped data into a structured CSV format.

## Prerequisites
To run this project, ensure you have the following installed:
1. **Python 3.x**: Make sure Python is installed on your machine.
2. **Selenium**: A Python library for web scraping and browser automation.
3. **ChromeDriver**: Ensure ChromeDriver is installed and compatible with your version of Chrome.

### Installation Instructions
1. **Install Selenium**:
   You can install Selenium using `pip`:
   ```bash
   pip install selenium
   '''
  2.**Run the script:**
  ```bash
  python flipkart_mobile_scraper.py
 ```
3. **The scraper will search for "mobiles under 10000" on Flipkart and scrape details like:**

Phone Name
Phone Price
Phone Rating
The scraped data will be saved in a CSV file named phones.csv in the same directory as the script.


