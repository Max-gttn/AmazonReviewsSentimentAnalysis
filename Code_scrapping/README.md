
**start project**
scrapy startproject amazon_reviews_scraping

**set html template**
scrapy genspider amazon_review your-link-here

**storing**
scrapy runspider amazon_reviews_scraping/amazon_reviews_scraping/spiders/Scrap_file.py -o data.csv
