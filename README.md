# 📊 Sales Data Analysis
A complete workflow for cleaning, transforming, and analyzing retail coffee sales data using Excel and Power Query.

## 🔍 Project Overview:
This project provides an end‑to‑end analysis of a multi‑sheet coffee sales dataset. It covers data preparation, merging, calculated fields, exploratory data analysis (EDA), and visualization. The goal is to transform raw operational data into meaningful insights using accessible tools.
The workflow includes:
- Cleaning and standardizing raw data
- Building a unified analytical dataset
- Exploring sales trends, product performance, and customer behaviour
- Visualizing insights using Pivot Tables and Pivot Charts

## 📁 Repository Contents: 
- `coffeeOrdersData.xlsx`: Raw dataset containing Products, Customers, and Orders.
- `data_cleaning_and_transformation.pq`: Power Query script used for data preparation.
- `visualizations.xlsx`: Pivot Tables and Pivot Charts.
- `README.md`: Documentation and methodology.


## 📦 Dataset Description:
The dataset (coffeeOrdersData.xlsx) contains three sheets:

### Products:
- Product ID
- Coffee Type
- Roast Type
- Size
- Unit Price
- Price per 100g
- Profit

### Customers:
- Customer ID
- Customer Name
- Email
- Phone Number
- Address Line1
- City
- Country
- Postcode
- Loyalty Card

### Orders:
- Order ID
- Order Date
- Customer ID
- Product ID
- Quantity
- Customer Name
- Email
- Country
- Coffee Type
- Roast Type
-  Size
- Unit Price
- Price per 100g
- Profit

## 🛠️ Tools: 
- Excel
- Power Query Editor
- Pivot Tables & Pivot Charts

## 🧹 Data Cleaning & transformation:
Data preparation was performed using Power Query Editor, following a structured sequence:
### Loading Data 
Imported all sheets from coffeeOrdersData.xlsx
### Handling Missing Values: 
- Identified nulls across customer and product fields
- Replaced or removed missing values where appropriate
### Data Type Correction:
- Converted numeric fields to proper types
- Ensured date fields were recognized correctly
### Merging Tables: 
Created a unified dataset by merging:
- Orders with Customers
- Orders with Products
This produced a single fact table containing all relevant attributes.
### Calculated Columns:
Added fields to support deeper analysis:
- Sales_Amount (Quantity × Unit Price)
- Month, Year, Day extracted from Order Date

The full transformation logic is stored in data_cleaning_and_transformation.pq.
   
## 📈 Exploratory Data Analysis:
Key analytical questions explored:

### What are the overall coffee sales trends?
Examined monthly and yearly patterns to identify seasonality and growth.

### How many customers hold loyalty cards by country?
Segmented customer base to understand loyalty distribution.

### Which coffee types are top sellers?
Compared product categories to identify high‑performing items.

### Which country generates the highest sales?
Analysed geographic performance to highlight strong markets.


## 📊 Data Visualization:

Visual insights were created using Pivot Tables and Pivot Charts:
- Sales Trend Line Chart
- Coffee Type Performance Chart
- Country‑wise Sales Distribution Bar Chart
- Loyalty Card Adoption Chart

All visualizations are available in visualizations.xlsx.

## ▶️ How to use this project: 
To replicate or extend the analysis:

1. Open coffeeOrdersData.xlsx in Excel
2. Load and apply transformations using Power Query Editor
3. Build Pivot Tables and Pivot Charts from the transformed dataset
4. Explore or modify the analysis based on new questions or hypotheses


### Contact:
For any questions or inquiries, please contact [revathigangadaran@gmail.com].

