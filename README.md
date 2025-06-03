# CodeAlpha_Webscraping
# 📘 Book Scraper - Web Scraping with Python

This project is part of my internship at **CodeAlpha**, where I worked on real-world data scraping using Python. It demonstrates how to collect structured information (titles, prices, and ratings) from an online book catalog.

---

## 🚀 About the Project

The goal was to scrape relevant book data from [Books to Scrape](http://books.toscrape.com) — a site designed for practicing web scraping — and build a mini dataset for future analysis or automation tasks.

**Scraped Data Includes:**
- Book Title
- Price (in £)
- Star Rating (e.g., One, Two, Three)

---

## 🧰 Tools & Libraries

- `requests` – for sending HTTP requests
- `BeautifulSoup` – for parsing HTML content
- `pandas` – for storing and displaying scraped data

---

## 🗂️ Features

✅ Navigates through multiple pages (1 to 3)  
✅ Extracts clean data using HTML structure  
✅ Stores data in structured lists  
✅ Ready for CSV export or analysis  

---

## 🏗️ How It Works

```python
# For each page in the range:
1. Send GET request to page
2. Parse the HTML with BeautifulSoup
3. Find all book containers
4. Extract title, price, and rating
5. Store them in Python lists
