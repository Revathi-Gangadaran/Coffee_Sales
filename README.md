# Coffee_Sales
Sales Performance of Coffee shop

### Project Overview:
This project aims to provide insights based on sales performance of coffee shop over past four years. By analysing various aspects of the sales data, we seek to identify the trend, make data-driven recommendations, and gain a deeper understanding of the company's perfromance.
### Data sources:

The primary dataset used for this analysis is the coffeeOrdersData.xlsx, containing informations about a coffee sale in three different countries.

### Tools: 
- Excel 
	- Power Query Editor- Data Cleaning
	- Pivot table - Data Analysis
	- Pivot Chart - Data Visualization

### Data Cleaning & Preparation:
In the initial data preparation phase, we performed the following task:
1. Data Loading and profiling
2. Handling missing values
3. Data Cleaning and formatting


### Exploratory Data Analysis:

EDA involved inexploring the sales data to answer the following questions:
1. What is the overall coffee sales trends?
2. How many people holds Loyalty card based on country?
3. Which coffee type are top sellers?
4. Which country made high sales?


### Data Analysis:

### Data Cleaning and preparation:

This part includes some interesting features to work with:
 - Added customised columns to calculate the sales amount of each order in Power Query Editor.

```
Sales_Amt = [Quantity]*[products.Unit Price]
```

 - Added Column to seggregate the data into different columns by its month, day, Year

```
= Table.AddColumn(#"Removed Columns", "Month", each Date.MonthName([Order Date]))

```
 - The same process is done for calculating day and year using Order Date Column

