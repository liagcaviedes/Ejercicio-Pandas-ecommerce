
# Ecommerce Purchases Data Analysis

## Project Overview

This project involves the analysis of a dataset containing simulated data from purchases made on an e-commerce platform, Amazon. The primary objective is to explore and answer various questions regarding the purchasing patterns, payment methods, customer details, and general insights using Pandas and NumPy libraries.

The dataset consists of 10,000 rows and 14 columns, and each row corresponds to an individual purchase made on the platform. The columns provide information such as customer details, credit card information, purchase prices, job titles, email addresses, and more.

The purpose of this project is to showcase the ability to handle and analyze large datasets using Python while producing meaningful insights from the data.

## Table of Contents
- Project Objective
- Dataset Description
- Key Insights
- Installation & Setup
- Analysis Steps
- How to Use
- Results Summary
- License


## Project Objective

The primary objectives of this project are:

- To analyze the customer purchase data and extract key insights.
- To answer specific business-related questions such as identifying the most common professions, popular email hosts, and credit card expiration trends.
- To practice and demonstrate data wrangling, manipulation, and analysis skills using Pandas and NumPy.
This project highlights the power of Python in data science, showcasing how even basic libraries can answer complex business questions.

## Dataset Description
The dataset used in this project contains the following columns:

- Address: Customer's address.
- Lot: Identifier for each purchase.
- AM or PM: The time of the purchase.
- Browser Info: Information about the browser used for the purchase.
- Company: Company associated with the customer.
- Credit Card: Credit card number used for the purchase.
- CC Exp Date: Credit card expiration date.
- CC Security Code: Credit card security code.
- CC Provider: Credit card provider (e.g., Visa, MasterCard).
- Email: Customer email address.
- Job: Customer's job title.
- IP Address: Customer's IP address.
- Language: Preferred language of the customer.
- Purchase Price: Price of the transaction.
- The data can be found here.

## Key Insights
Some of the key insights derived from the data include:

- Mean Purchase Price: The average purchase price across all transactions.
- Max/Min Purchase Price: The highest and lowest purchase price in the dataset.
- Top Professions: The five most common job titles among customers.
- Morning vs. Afternoon Purchases: The distribution of purchases made during AM vs PM.
- Top Email Hosts: The most popular email domains among customers (e.g., Gmail, Yahoo).
- American Express Usage: The number of customers using American Express and spending more than $95.
- Credit Card Expiration in 2025: The number of credit cards expiring in the year 2025.

## Installation & Setup
To run the analysis, follow these steps:

1. Clone the Repository:

bash
Copiar código
git clone https://github.com/YourUsername/ecommerce-purchases.git
cd ecommerce-purchases

2. Install Dependencies: Make sure you have Python 3.x installed and install the required packages using pip:

bash
Copiar código
pip install pandas numpy

3. Run the Jupyter Notebook: If using Jupyter Notebook, simply open the .ipynb file and execute the cells sequentially to perform the analysis.

## Analysis Steps
1. Data Loading & Inspection: Load the dataset using Pandas and inspect the first few rows to understand the structure.
2. Basic Descriptive Statistics: Compute key statistics like the average, max, and min purchase prices.
3. Data Filtering & Querying: Use Pandas to answer specific business questions (e.g., customers with a certain job title, email provider, or credit card type).
4. Exploratory Data Analysis (EDA): Investigate patterns in the data such as time-of-day purchases and language preferences.
5. Summarize Results: Present the findings in a concise manner, summarizing key insights derived from the data.

## How to Use
You can run the analysis using the following methods:

- Jupyter Notebook: If you're familiar with Jupyter, you can open the analysis notebook and execute each cell to see the results. The code is structured to answer the proposed questions progressively.

- Python Script: You can also execute the analysis as a Python script by running the following command:

bash
Copiar código
python ecommerce_analysis.py

### Author
- **Name**: Rosalía González Caviedes
- **Email**: rosaliagonzalezc@gmail.com
- [LinkedIn profile](https://www.linkedin.com/in/rosaliagonzalezcaviedes/)
- [Github profile](https://github.com/liagcaviedes)

### License
This project is licensed under the MIT License 


 
