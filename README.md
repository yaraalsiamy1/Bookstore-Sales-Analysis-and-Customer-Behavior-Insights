# Bookstore Sales Analysis and Customer Behavior Insights

## Project Overview
This project focuses on analyzing bookstore sales data to understand customer behavior and purchasing patterns. The goal is to extract meaningful insights that support better decision-making and improve the overall bookstore performance.


## Objectives
- Analyze customer behavior and identify popular books  
- Determine peak (rush) hours to improve staff allocation  
- Identify the best-selling book categories  
- Support data-driven decision making  


## Dataset Information
- Dataset: Bookstore Sales Records (2018–2019)
- Source: [Kaggle Dataset - Books Sales and Ratings](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings)  
- Total records: 3480 rows  
- Initial features: 68 columns, reduced to 22 after cleaning  
- Categories:
  - School  
  - College  
  - Competition  


## Data Cleaning
The dataset was preprocessed using the following steps:
- Removing duplicate rows and columns  
- Dropping unnecessary columns  
- Handling outliers using the IQR method  
- Standardizing values (e.g., "School" to "school")  
- Checking for missing values (none found)  


## Exploratory Data Analysis
The analysis includes:
- Product Name Analysis to identify best-selling books  
- Authors Analysis to determine the most popular authors  
- Category Analysis to find the highest selling category  


## Feature Engineering
New features were created:
- TotalPrice = Item Price + Shipping Price  
- TotalQuantityPerCustomer = total number of purchases per customer  


## Key Insights
- The "school" category has the highest sales  
- Certain books and authors dominate customer preferences  
- Morning time represents a peak period for purchases  


## Tools and Technologies
- Python  
- Pandas  
- Matplotlib  
- Google Colab  
