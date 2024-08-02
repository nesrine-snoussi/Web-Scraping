# Web Scraping Script

This repository contains a Jupyter Notebook to scrape articles and documents related to public health in Tunisia from various websites.

## Description

The notebook performs the following tasks:

1. **Fetch HTML content**: Uses `requests` to fetch HTML content from a list of specified URLs.
2. **Extract text from HTML**: Uses `BeautifulSoup` to extract text and links from the HTML content.
3. **Filter and save relevant data**: Filters articles and documents related to Tunisia and saves the URLs and titles to a CSV and Excel file.

## Installation

To run the notebook, you need to install the following Python libraries:

- `requests`: For sending HTTP requests to fetch the HTML content of web pages.
- `beautifulsoup4`: For parsing the HTML content and extracting the data.
- `pandas`: For organizing the extracted data into a structured format and saving it to CSV.

Install them using `pip`:

```bash
pip install requests beautifulsoup4 pandas 
