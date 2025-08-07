# IPhone Data Scraping Project (Flipkart)
This project focuses on web scraping iPhone product data from Flipkart, one of India's leading e-commerce platforms. The goal is to extract key product information such as:

 iPhone Model Name
 Price
 Display Size
 Processor
 Camera Details
 Storage (ROM)
 Rating
 Discount

## Tools & Technologies Used:

 Python (Google coolab)
 BeautifulSoup – for parsing HTML content
 Requests – for sending HTTP requests
 Pandas – for organizing and exporting data

## Project Workflow:
 
 Sent requests to Flipkart's search results pages.
 Parsed the HTML response using BeautifulSoup.
 Extracted the required product details using relevant div, span, and li tags.
 Cleaned and structured the data.
 Exported the final dataset into a .csv file for further analysis.

## Key Challenges & Learning Outcomes:

 Identifying the correct HTML structure and dynamic classes for consistent scraping.
 Overcame issues like getting None values due to missing or misidentified tags.
 Learned how to handle and export structured data using Pandas.
 Implemented time delays to avoid request blocking and simulate natural browsing.
 Gained a deeper understanding of how to collect and analyze real-world data from the web.
 Strengthened skills relevant to data analytics and preprocessing.

## Output:

 The scraped data is saved in a CSV file (iphone_data.csv), which can be further used for:
 Market analysis
 Price comparison
 Feature-based product filtering

 ## Scraped Data
 - <a href = "https://github.com/vanshdhiman090/web_scraping/blob/main/iphone_scrape_data.csv"> Iphones_Scraped_Data </a>

 ## Code for Scraping
 - <a href = "https://github.com/vanshdhiman090/web_scraping/blob/main/webscrape.ipynb"> Google_Coolab_Code </a>
