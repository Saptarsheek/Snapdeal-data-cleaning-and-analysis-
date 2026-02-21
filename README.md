# Snapdeal-data-cleaning-and-analysis-
 Snapdeal Data Analysis & Data Cleaning Project

📌 Project Overview

This project focuses on web scraping, data cleaning, exploratory data analysis (EDA), and visualization of product data from Snapdeal. The objective was to extract raw product information from the website, transform it into a structured dataset, clean inconsistencies, and generate meaningful insights using Python.

The project demonstrates an end-to-end data workflow — from data extraction to analysis and visualization.

Technologies & Libraries Used

* `requests` – To send HTTP requests and retrieve webpage data
* `BeautifulSoup (bs4)` – For parsing HTML content and extracting product information
* `pandas` – For data cleaning, manipulation, and analysis
* `matplotlib` – For foundational data visualizations
* `seaborn` – For advanced and statistical visualizations

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

Project Workflow
1.Web Scraping

* Sent HTTP requests to Snapdeal product pages using `requests`
* Parsed the HTML structure using `BeautifulSoup`
* Extracted relevant product attributes such as:

  * Product Name
  * Price
  * Discount Percentage
  * Ratings
  * Category (if available)

 2.Data Cleaning & Preprocessing

* Removed duplicate records
* Handled missing/null values appropriately
* Cleaned price columns (removed currency symbols and converted to numeric format)
* Standardized rating values
* Converted data types for accurate analysis
* Structured the dataset into a clean Pandas DataFrame

3.Exploratory Data Analysis (EDA)

Performed analysis to:

* Understand price distribution
* Analyze rating trends
* Examine discount patterns
* Compare categories based on pricing
* Identify high-performing products

4.Data Visualization

Created visualizations using Matplotlib and Seaborn, including:

* Price distribution histograms
* Box plots for price comparison
* Bar charts for category-level insights
* Correlation heatmaps (if applicable)

>Key Insights

* Identified common pricing ranges across products
* Observed trends between discounts and customer ratings
* Highlighted top-rated products within specific price segments
* Analyzed category-wise pricing behavior

> Project Structure

Snapdeal-Data-Analysis/
│
├── data_scraping.py
├── data_cleaning_analysis.ipynb
├── cleaned_dataset.csv
└── README.md

> Learning Outcomes

* Hands-on experience in web scraping using Python
* Strengthened data cleaning and preprocessing skills
* Applied exploratory data analysis techniques
* Improved data visualization and storytelling skills
* Developed structured thinking for real-world datasets

!!!Disclaimer!!!

This project was created for educational and portfolio purposes only.

If you want, I can now make a slightly more advanced, recruiter-impressive version that highlights impact more strongly.

