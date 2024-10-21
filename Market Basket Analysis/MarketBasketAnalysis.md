# Project Title
Online Retail Dataset
## Project Overview
This project aims to perform Market Basket Analysis (MBA) using sales transaction data from an online retail store. Market Basket Analysis is a popular data mining technique used to uncover associations between products that are frequently bought together by customers. The insights derived from this analysis can help businesses improve decision-making in areas like inventory management, sales promotions, and product recommendations.
In this project, we leverage the FP-Growth algorithm,to identify frequent itemsets and generate association rules.
## Dataset 
 - Dataset Name: OnlineRetail.csv
 - Source:( https://www.kaggle.com/code/hassanamin/market-basket-analysis-for-online-retail-dataset/notebook )
 - File Format: CSV
 - Encoding: latin1
## Libraries Used
To run the code successfully, the following Python libraries are required:
 - pandas: For data loading and manipulation.
 - mlxtend: For applying Market Basket Analysis using the Apriori algorithm and association rules.
 - numpy: For handling numerical operations.
 - matplotlib or seaborn: For data visualization.
   
## How to Run the Code
Step 1: Clone or Download the Repository
 - Download the project files or clone the repository to your local machine

Step 2: Place the Dataset
 - Ensure that the ( OnlineRetail.csv)file is placed in the project folde

Step 3: Execute the Python Script
Run the provided Python script to perform Market Basket Analysis using the FP-Growth algorithm. The script will:
 - Load the dataset using pandas.
 - Preprocess the data by grouping items by invoice number.
 - Apply one-hot encoding to prepare the data for the FP-Growth algorithm.
 - Execute the FP-Growth algorithm to find frequent itemsets.
 - Generate association rules to uncover relationships between purchased item

Step 4: View the Results
 - After execution, the script will display the top 10 association rules, showing which items are frequently bought together. You can customize the support and confidence thresholds to fine-tune the results according to your need

## How the Dataset Was Used
1- Data Preprocessing:
 - The dataset was grouped by the InvoiceNo field to aggregate items for each transaction.
 - One-hot encoding was applied to convert the dataset into a format suitable for the FP-Growth algorithm.

2- Market Basket Analysis:
 - The FP-Growth algorithm was applied to identify frequent itemsets with a minimum support of 0.01 (i.e., 1% of transactions).
 - Association rules were generated to discover relationships between items frequently bought together, with a minimum lift of 0.5

3- Analysis Goal:
 - The goal of this analysis is to identify relationships between products that are frequently purchased together, which can help in inventory management, sales promotions, and recommendation systems.






