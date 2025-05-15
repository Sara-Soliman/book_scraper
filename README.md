# 📚 BookStore Web Scraper

This Python project scrapes product information from [Books to Scrape](http://books.toscrape.com), a site designed for scraping practice.

## 🔍 What It Scrapes
- Book title
- Price
- Availability
- Rating (1–5 stars)
- Link to product page

## 🛠️ Tools Used
- `requests` – fetches the webpage
- `BeautifulSoup` – parses and extracts the HTML
- `pandas` – stores and saves data in CSV format

## 📂 Output
A `books.csv` file with structured data—perfect for eCommerce research, market analysis, or dashboard use.

## 🚀 Usage
Run this script in a Python environment:
```bash
python scraper.py
