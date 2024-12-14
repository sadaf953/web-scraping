# Web Scraping Explorer 🕸️

## Overview
This is a simple Streamlit application that allows you to scrape basic information from websites, including titles, headings, links, and paragraphs.

## Prerequisites
- Python 3.7+
- Streamlit
- Requests
- BeautifulSoup4

## Installation
1. Clone the repository
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application
```bash
streamlit run app.py
```

## Features
- Enter any website URL
- Extract website title
- Retrieve headings
- List website links
- Show paragraphs

## Usage Notes
- Only http and https URLs are supported
- The app limits output to prevent overwhelming results
- Respects website robots.txt and uses a user agent

## Disclaimer
- Use responsibly and respect website terms of service
- Web scraping may be against some websites' policies

## Contributing
Feel free to open issues or submit pull requests!
