# Capstone_2 – Sales Territory Analysis (Northeast Region)

## Author

## Dimitri Nji

## Project Overview

This project analyzes in-store sales performance for two assigned sales territories in the Northeast region:

Maine — Territory Manager: Erbayne Middleton
New Jersey — Territory Manager: Miami Vue

The purpose of this project is to compare sales performance, customer activity, store performance, and product category trends across both territories. The analysis was completed using Python, Pandas, and Matplotlib inside a Jupyter Notebook environment.

### The final project includes:

Data cleaning and preparation
Data merging across multiple CSV files
Sales analysis by territory
Customer and store performance analysis
Product category analysis
Data visualizations and charts
Marketing recommendations for the next quarter
Technologies Used
Python
Pandas
Matplotlib
Jupyter Notebook
Git & GitHub
Files Used

### The following datasets were used in this analysis:

StoreSales.csv
StoreDetail.csv
Products.csv
ProductCategories.csv
customer_list.csv
Project Questions Answered

### This project answers the following business questions:

Who are the territory managers for the assigned territories?
Which stores belong to each assigned territory?
What is the monthly total revenue for in-store sales?
Which stores are the top-performing stores?
Who are the top customers in each territory?
What are the transaction trends by product category?
What product categories generate the most revenue?
What marketing recommendations should be made for next quarter?
Data Analysis Process
### 1. Data Import and Inspection

All CSV files were imported into Pandas DataFrames and reviewed using:

.info()
.head()

This helped verify:

Column names
Data types
Missing values
### 2. Data Cleaning

The data was cleaned by:

Removing extra spaces from column names
Replacing spaces with underscores
Converting transaction dates into datetime format
Creating monthly grouping columns
### 3. Data Merging

The datasets were merged together using:

Store_ID
Prod_Num
CategoryID
RewardsID
cust_id

This created one complete dataset for analysis.

### 4. Sales Analysis

The project analyzed:

Monthly revenue trends
Store rankings
Customer spending
Product category performance
Transaction counts
### 5. Data Visualization

Charts were created using Matplotlib, including:

Line charts
Bar charts

All charts and tables were automatically saved into the capstone_outputs folder.

### Key Findings
Some stores consistently outperformed others in total revenue.
Certain product categories generated significantly more sales and transactions.
Rewards customers contributed strongly to repeat purchases.
Some stores and categories showed opportunities for growth through additional marketing support.

### Final Recommendation

The marketing team should focus next quarter on:

Supporting lower-performing stores
Promoting weaker product categories
Using top rewards customers for targeted campaigns
Applying successful strategies from top-performing stores to weaker locations
