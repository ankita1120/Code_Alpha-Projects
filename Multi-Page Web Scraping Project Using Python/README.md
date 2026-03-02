📌 Project Title

Multi-Page Web Scraping and Exploratory Data Analysis Using Python

📖 Project Overview

This project demonstrates web scraping and data extraction techniques using Python.

The objective was to scrape book information from the Books to Scrape website and perform basic data cleaning and exploratory analysis.

A total of 100 books were scraped from 5 pages of the website.

🎯 Objectives

Extract book data from multiple web pages

Clean and preprocess scraped data

Convert price column into numeric format

Perform basic exploratory data analysis (EDA)

Export structured dataset as CSV

🛠️ Technologies Used

Python

Requests

BeautifulSoup

Pandas

Matplotlib

📊 Data Extracted

The following attributes were collected:

Title

Price

Rating

Availability

🔍 Data Cleaning

Removed currency symbols (encoding issues like Â£)

Converted Price column from string to float

Handled potential missing values

📈 Key Insights

Total Books Scraped: 100

Average Book Price calculated

Distribution of book ratings analyzed

Basic visualization created using Matplotlib

📂 Project Structure
WebScraping_Project/
│
├── books_scraping.ipynb
├── books_data.csv
├── README.md
🚀 How to Run the Project

Install required libraries:

pip install requests beautifulsoup4 pandas matplotlib

Run the Python notebook or script.

💡 Learning Outcomes

Understanding HTML structure

Handling pagination in web scraping

Fixing real-world encoding issues

Data cleaning and preprocessing

Performing basic EDA

👩‍💻 Author

Ankita