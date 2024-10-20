# Project Title
Online Retail Dataset
## Dataset Overview
This dataset represents sales transactions from an online retail store. It contains various details about each transaction, including the invoice number, product description, quantity sold, price per unit, customer details, and the country of the customer. This data is suitable for performing Market Basket Analysis (MBA) and other analyses of purchasing behavior.
## Dataset 
 - Dataset Name: OnlineRetail.csv
 - Source:( https://www.kaggle.com/code/hassanamin/market-basket-analysis-for-online-retail-dataset/notebook )
 - File Format: CSV
 - Encoding: Latin-1
## Libraries Used
To run the code successfully, the following Python libraries are required:
 - pandas: For data loading and manipulation.
 - mlxtend: For applying Market Basket Analysis using the Apriori algorithm and association rules.
 - numpy: For handling numerical operations.
 - matplotlib or seaborn: For data visualization.
   # Install Libraries
   you can use this:
  ( pip install pandas mlxtend numpy matplotlib seaborn )
## How to Run the Code
Step 1: Clone or Download the Repository
 - Start by downloading the project files or cloning the repository to your local machine.

Step 2: Place the Dataset
 - Ensure that the dataset file OnlineRetail.csv is placed in the project folder.

Step 3: Run the Python Script
Run the provided Python script to perform Market Basket Analysis on the dataset. The script will:
 - Load the dataset.
 - Preprocess the data by grouping items by invoice number.
 - Apply one-hot encoding to prepare the data for the Apriori algorithm.
 - Run the Apriori algorithm to find frequent itemsets.
 - Generate association rules to discover relationships between items.

Step 4: View Results
 - After running the script, the output will display the top 10 association rules that reveal which items are frequently bought together.You can customize the threshold values for support and confidence to tune the results according to your needs.

## How the Dataset Was Used
1-Data Preprocessing:
 - The Description field in the dataset was grouped by InvoiceNo to create lists of items for each transaction.
 - One-hot encoding was applied to transform the dataset into a format suitable for Market Basket Analysis.
   
2-Market Basket Analysis:
 - The Apriori algorithm was applied to find frequent itemsets with a minimum support of 0.01 (1% of transactions).
 - Association rules were generated to identify product combinations that occur together frequently with a minimum lift threshold of 0.5.
   
3-Analysis Goal:
 - The analysis aimed to discover relationships between products frequently purchased together to help with inventory management, sales promotions, and product recommendation systems.









