# Tour Operator Scraper 

Scraper for creating initial datasets on hotels, available transport methods, departure / arrival destinations, hotel room types, and tour options for the target application.

## Pre-requirements

- Python 3.12

## Installation

It is recommended that you install this application's dependencies in a virtual environment:

### Linux/macOS

```
python3.12 -m venv .venv
source .venv\bin\activate
python -m pip install -r requirements.txt
```

## Usage

To both scrape and parse the scraped data, run:
```
python scrape.py results/
```

To skip scraping, run:
```
python scrape.py --skip-scraping results/
```
