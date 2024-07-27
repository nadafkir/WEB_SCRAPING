### WEB SCRAPING  

# Project Overview

In this project, I developed a web scraping tool using Python to extract and analyze data from the website "Books to Scrape". Leveraging libraries such as `requests`, `BeautifulSoup`, and `pprint`, the tool retrieves and parses HTML content to gather information about books listed on the site.

## Key Features

### Data Extraction

- **Images:** Extracted image URLs and descriptions.
- **Categories:** Retrieved book categories and their URLs.
- **Books:** Collected details on each book including title, price, availability, and product ID.

### Category Analysis

- **Category Statistics:** Counted the number of books in each category.

### Sentiment Analysis

- Utilized the `TextBlob` library to analyze the sentiment of book reviews and descriptions. This involves extracting the text data and computing sentiment scores to gauge the overall sentiment of the content.
