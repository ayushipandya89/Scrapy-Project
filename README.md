# Scrapy-Blog-Project

This is a Scrapy project designed to scrape data from the [Books to Scrape](https://books.toscrape.com) website. The data scraped includes the URL, title, UPC, product type, prices, availability, reviews, rating stars, category, description, and price of each book.


## Technologies Used

- Python
- Scrapy


## Install Python

```bash
    sudo apt install python3
```


## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ayushipandya89/Scrapy-Project.git
    cd book_scraper
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```


## Usage

1. **Navigate to the project directory**:
    ```bash
    cd book_scraper
    ```

2. **Run the Scrapy spider**:
    ```bash
    scrapy crawl books
    ```

3. **Output**:

    The scraped data will be saved to a file (e.g., `output.json`) as specified in your Scrapy settings or command.
