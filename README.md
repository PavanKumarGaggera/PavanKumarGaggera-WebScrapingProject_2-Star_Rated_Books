# WebScrapingProject_2-Star_Rated_Books

# Web Scraping Project: Extracting Titles of 2-Star Rated Books

This Python web scraping project aims to extract the titles of books with a 2-star rating from the [Books to Scrape](http://books.toscrape.com) website.

## Project Overview

The project involves the following steps:

1. Determine the URL structure to navigate through each page of the catalogue.
2. Scrape information from every page in the catalogue.
3. Identify the HTML tag/class that represents the star rating.
4. Filter books with a 2-star rating using conditional statements.
5. Store the results in a Python list.

## Usage

To run the script and obtain the list of 2-star rated book titles, follow these steps:

1. Install the required libraries:

    ```bash
    pip install requests beautifulsoup4
    ```

2. Open the `scrape_books.py` file and run it.

    ```bash
    python scrape_books.py
    ```

   This will iterate through the pages, scrape the titles, and store them in the `two_star_titles` list.

## Code Structure

The main script is `scrape_books.py`, which includes:

- URL structure definition.
- Loop to iterate through pages.
- Web scraping logic using `requests` and `BeautifulSoup`.
- Filtering based on the star rating.
- List to store the titles.

## Dependencies

- [Requests](https://docs.python-requests.org/en/latest/) for making HTTP requests.
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for HTML parsing.

## Results

After running the script, the extracted titles will be stored in the `two_star_titles` list.

## Disclaimer

This project is intended for educational purposes only. Make sure to review and respect the terms of service of the website you are scraping.

Happy coding!
