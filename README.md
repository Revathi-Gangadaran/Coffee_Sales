# Coffee Shop Sales Data Analysis

## Project Overview:
This project contains the analysis of a coffee shop's sales data. The dataset includes orders, products, and customer information stored in a single Excel file. Data cleaning and transformation were performed using Power Query Editor, and visualizations were created using Pivot Tables and Pivot Charts in Excel.

## Contents: 
- `coffeeOrdersData.xlsx`: The main Excel file containing three sheets with data.
- `README.md`: Documentation file providing an overview of the project and analysis steps.
- `data_cleaning_and_transformation.pq`: Power Query script for data cleaning and transformation.
- `visualizations.xlsx`: Excel file with Pivot Tables and Pivot Charts for visualization.

The primary dataset used for this analysis is the , containing informations about a coffee sale in three different countries.

## Tools: 
- Excel
- Power Query Editor
	
## Dataset Description:
The dataset is stored in coffeeOrdersData.xlsx and includes the following sheets:

### Sheet1: Products:
- Product ID
- Coffee Type
- Roast Type
- Size
- Unit Price
- Price per 100g
- Profit

### Sheet2: customers:
- Customer ID
- Customer Name
- Email
- Phone Number
- Address Line1
- City
- Country
- Postcode
- Loyalty Card

### Sheet3: orders:
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
  

## Data Cleaning & transformation:
Data cleaning and transformation were performed using Power Query Editor. The steps included:
1. Loading Data: Importing data from the coffeeOrdersData.xlsx file.
2. Handling Missing Values: Identifying and filling in or removing missing data.
3. Correcting Data Types: Ensuring that numerical columns are set to the correct data type and dates are recognized correctly.
4. Merging Data: Merging Orders, Products, and Customers sheets to create a comprehensive dataset for analysis.
5. Creating Calculated Columns: Adding columns such as Sales_Amount, Month, Year and Day from Date column to facilitate analysis.
   
The Power Query script used for these steps is saved as data_cleaning_and_transformation.pq.

## Exploratory Data Analysis:
It is an approach to analyse the dataset to summarise their main characteristics by using visual methods. 

EDA involved in this project to explore the sales data to answer the following questions:
1. What is the overall coffee sales trends?
2. How many people holds Loyalty card based on country?
3. Which coffee type are top sellers?
4. Which country made high sales?


## Data Visualization:

Visualizations were created using Pivot Tables and Pivot Charts in Excel to explore and analyze the cleaned data. Key visualizations include:
1. Sales trend analysis: A Line chart with markers displays the sales trends over time.
2. Product Performance: A stacked line chart comparing sales of different types of coffee.
3. Customer Location Analysis: Clustered bar chart visualizes sales distribution by customer location based on their coffee type.
4. Customer Loyalty: A clustered bar char displays the total customers that holds loyalty cards in different country.

The visualizations are saved in the visualizations.xlsx file.


## How to use: 
To replicate the analysis:
1. Open the coffee_shop.xlsx file in Excel.
2. Use Power Query Editor to load and transform the data according to the steps outlined in data_cleaning_and_transformation.pq.
3. Create Pivot Tables and Pivot Charts based on the transformed data to visualize and analyze sales trends.


### Contact:
For any questions or inquiries, please contact [revathigangadaran@gmail.com].

