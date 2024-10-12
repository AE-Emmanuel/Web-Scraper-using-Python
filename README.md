
# Web Scraper using Python (Requests & BeautifulSoup)

Welcome to the Web Scraper repository! This project is a simple web scraper that extracts text, links, and images from a specified webpage using Python's requests and BeautifulSoup libraries.


## Overview

This project serves as an introduction to web scraping with Python. By providing a webpage URL, the scraper will:

    Extract and print all the visible text on the page.
    Collect all hyperlinks found on the page.
    Gather all image URLs from the webpage.

The project is suitable for anyone learning Python and web scraping, and it provides a basic structure to expand into more complex scraping projects.
Features

    Requests: To send GET requests and retrieve webpage content.
    BeautifulSoup: For HTML parsing and data extraction.
    Text Extraction: Retrieves and prints all visible text from the page.
    Link Extraction: Gathers all URLs from <a> tags.
    Image Extraction: Collects all image URLs from <img> tags.

## Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/web-scraper-python.git
cd web-scraper-python

Install the required dependencies:

bash

pip install -r requirements.txt

(Create a requirements.txt file with the following content if needed):

txt

    requests
    beautifulsoup4

## Usage

    Open the web_scraper.py file.

    Modify the url variable in the script to the webpage you want to scrape.

    python

url = "https://example.com"

Run the script:

bash

    python web_scraper.py

    The output will display the extracted text, links, and images from the specified webpage.

Example

The script can be used on any public webpage. Here’s an example output for a given webpage:

bash

Texts From Webpage:
[Visible text from the webpage...]

Links From Webpage:
https://example.com/link1
https://example.com/link2

Images From Webpage:
https://example.com/image1.jpg
https://example.com/image2.png
