# 🛒 Shopify Store Crawler and Scraper 🕷️

This script crawls and scrapes Shopify e-commerce sites to generate LLM-ready documents for a brand's store.

## 🚀 Features

- 🕸️ Crawls entire Shopify store
- 📃 Generates a full sitemap
- 🏷️ Extracts product information
- 🧹 Cleans and structures data using GPT-4
- 💾 Saves product data in JSON format

## 🛠️ Setup

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your `.env` file with your OpenAI API key

## 🏃‍♂️ How to Run

1. Run the script: `python shopify_scraper.py`
2. Enter the homepage URL of the Shopify store you want to crawl
3. Wait for the crawling and processing to complete

## 📁 Output

- A folder named after the store's domain
- `full_sitemap.txt` containing all crawled URLs
- JSON files for each product with extracted and cleaned information

## ⚠️ Note

Please use this script responsibly and in accordance with the website's robots.txt file and terms of service.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
