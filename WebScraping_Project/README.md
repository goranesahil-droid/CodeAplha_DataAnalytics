# Largest U.S. Companies by Revenue - Web Scraping Project

## Overview

This project demonstrates web scraping using Python by extracting data from the Wikipedia page:

**"List of Largest Companies in the United States by Revenue"**

The scraped data is transformed into a structured dataset and exported as a CSV file for further analysis and reporting.

## Project Objective

The objective of this project is to:

* Collect tabular data from a live web page.
* Parse HTML content using Python.
* Convert extracted information into a structured format.
* Export the cleaned dataset for analysis.

## Data Source

Source:

* Wikipedia – List of Largest Companies in the United States by Revenue

The dataset contains information about major U.S. companies ranked by revenue.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Google Colab

## Workflow

1. Send a request to the Wikipedia page.
2. Retrieve the HTML content.
3. Locate the target table containing company information.
4. Extract table headers and rows.
5. Store the data in a Pandas DataFrame.
6. Perform basic data cleaning.
7. Export the final dataset as a CSV file.

## Project Structure

```text
Largest-US-Companies-Web-Scraping/
│
├── WebScraping.ipynb
├── Companies.csv
├── requirements.txt
└── README.md
```

## Sample Data Fields

The scraped dataset includes fields such as:

* Rank
* Company
* Industry
* Revenue (USD Millions)
* Revenue Growth
* Employees
* Headquarters


## Output

The final output is a CSV file containing structured company information extracted from Wikipedia.

Example:

| Rank | Company | Industry   | Revenue |
| ---- | ------- | ---------- | ------- |
| 1    | Walmart | Retail     | 648,125 |
| 2    | Amazon  | E-commerce | 574,785 |
| 3    | Apple   | Technology | 383,285 |

## Learning Outcomes

Through this project, I gained practical experience in:

* Web Scraping
* HTML Parsing
* Data Extraction
* Data Cleaning
* Data Manipulation using Pandas
* Exporting Data to CSV
* Working with Real-World Data Sources

## Future Enhancements

* Automate data updates.
* Scrape multiple company ranking pages.
* Perform exploratory data analysis (EDA).
* Build visualizations and dashboards from the collected data.

## Author

Sahil

Aspiring Data Analyst | Python | SQL | Data Visualization | Machine Learning

