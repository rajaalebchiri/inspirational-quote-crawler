# Inspirational Quote Crawler

**overview**

This project showcases the integration of Flask and Scrapy to create a dynamic web application that extracts inspirational  quotes from https://quotes.toscrape.com/.

**Features**

- Efficient Scraping: Scrapy crawls https://quotes.toscrape.com/tag/inspirational/page/1/ , efficiently retrieving inspirational quotes.
- Dynamic Web Interface: Flask renders the scraped quotes on a user-friendly website.
- Organized Storage:  Stores scraped quotes in a structured format JSON for future reference or analysis.

**Technologies Used**

- Scrapy: Powerful web scraping framework
- Flask: Lightweight and adaptable Python web framework
- Jinja2: Templating engine for creating dynamic web content

## Getting Started

**Prerequisites:**

Python 3.x
Virtual environment (recommended)
Basic understanding of Flask and Scrapy
Installation

1. Clone the repository:

```
git clone https://github.com/<your_username>/success-quote-crawler.git
cd success-quote-crawler
```

2. Create a virtual environment and activate it:

```
python3 -m venv venv
source venv/bin/activate 
```

3. Install Requirements:

```
pip install -r requirements.txt
```

**Usage**

Run the app:

```
python main.py
```

Access the application in your web browser, typically at http://127.0.0.1:5050/
