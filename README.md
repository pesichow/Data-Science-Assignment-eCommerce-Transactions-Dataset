# Data-Science-Assignment-eCommerce-Transactions-Dataset
Project Overview
This project involves analyzing an eCommerce dataset that includes information about customers, products, and transactions. The tasks are divided into three parts:

Exploratory Data Analysis (EDA) to clean and explore the dataset, identify patterns, and derive actionable business insights.
Lookalike Model to recommend similar customers based on profile and transaction history.
Customer Segmentation using clustering techniques to group customers based on their behaviors and attributes.
Steps to Run the Code
Download and Prepare Datasets:

Save the provided CSV files (Customers.csv, Products.csv, Transactions.csv) in the same directory as your code.
Install Dependencies:

Ensure the following Python libraries are installed:
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn fpdf scikit-learn
Run Task 1 (EDA):

Execute the EDA script provided for Task 1 to clean and analyze the datasets.
The script will:
Identify missing values and duplicates.
Convert date columns to the correct format.
Generate summary statistics for numeric fields.
Extract insights into product prices, transaction values, and quantities.
Generate EDA Report:

A PDF report summarizing the EDA results will be automatically generated if you use the PDF generation code.
Proceed to Task 2 (Lookalike Model):

Once the datasets are clean, use the merged data to build a Lookalike Model.
Train the model, and generate similarity scores for customer recommendations.
Run Task 3 (Clustering):

Use clustering algorithms (e.g., K-Means) to group customers and calculate evaluation metrics like DB Index.
Dependencies
Here are the main libraries you'll need:

pandas: For data manipulation and cleaning.
numpy: For numerical computations.
matplotlib and seaborn: For visualizing trends and patterns in the data.
fpdf: To generate PDF reports summarizing EDA insights.
scikit-learn: For machine learning models (e.g., Lookalike and Clustering).
