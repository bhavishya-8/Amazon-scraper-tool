# Amazon Product Scraping
![Running GIF](https://camo.githubusercontent.com/1140a4f2ffe1d7d5432df78421909e56c97909423568e609983ec3d4fbcb0b22/68747470733a2f2f726561646d652d747970696e672d7376672e6865726f6b756170702e636f6d3f666f6e743d4f72626974726f6e2673697a653d343026636f6c6f723d253233373941353030266865696768743d3637266475726174696f6e3d333030302663656e7465723d74727565266c696e65733d254630253946253835254236254630253946253836253831254630253946253835254234254630253946253835254234254630253946253836253833254630253946253835254238254630253946253835254244254630253946253835254236254630253946253836253832)


This Python script allows you to scrape product details from Amazon search results. It utilizes the `requests` library for making HTTP requests and the `BeautifulSoup` library for parsing HTML content. The scraped details include product names, prices, URLs, ratings, and the number of reviews.

## Usage

1. **Prerequisites:** Make sure you have Python installed on your system. You can install the required libraries using the following commands:


2. **Running the Script:**

- Open the `amazon_scraping.py` script in a code editor of your choice.
- Adjust the `base_url`, `search_query`, and `num_pages_to_scrape` variables as needed.
- Run the script. It will scrape product details from Amazon search results.

3. **Output:**

The script will collect product details and store them in separate lists: `product_names`, `product_prices`, `product_urls`, `ratings`, and `num_reviews`.

Optionally, you can uncomment the loop at the end to print the scraped details for each product.

## Advantages

- **Automated Data Collection:** This script automates the process of collecting product details from Amazon search results. It saves time and effort compared to manual data collection.

- **Customizable:** You can easily adjust the search query and number of pages to scrape based on your requirements.

- **Structured Data:** The script organizes the scraped data into separate lists for each detail (name, price, URL, etc.), making it easy to process or export to other formats.

- **Bypassing Pagination:** The script handles pagination by looping through the specified number of pages, so you can gather a larger dataset.

- **Expandable:** You can build upon this script to add more features, such as storing data in a CSV file, integrating with a database, or even performing sentiment analysis on product reviews.

## Disclaimer

Please be aware that web scraping may be subject to terms of use and legal restrictions on certain websites. Make sure to review Amazon's terms of service and robots.txt file before using this script for scraping purposes.
![Running GIF](  https://raw.githubusercontent.com/trinib/trinib/82213791fa9ff58d3ca768ddd6de2489ec23ffca/images/footer.svg)
