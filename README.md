# Executive Sales Dashboard (Power BI)

An end to end Power BI project that turns raw Excel sales data into an interactive executive dashboard. The project covers data cleaning, data modelling, DAX measures and dashboard design.

## Dashboard Preview

![Executive Sale Dashboard](Executive_Sales_Dashboard_PowerBI/Images/Executive%20Sale%20Dashboard.png)

## Project Objective

To track business performance across countries, product categories and sales channels using clear KPIs and interactive filters so that decision makers can understand the numbers in seconds.

## Key KPIs

* Total Revenue: 645.22K
* Total Gross Profit: 296.38K
* Gross Margin: 45.94%
* Total Quantity Sold: 6,698
* Total Orders: 2,707

## Project Workflow

1. Imported the raw sales data from Excel into Power BI
2. Cleaned and transformed the data in Power Query
3. Created a Date Calendar table and a Data table
4. Linked these tables to the sales data using relationships
5. Wrote DAX measures for every KPI
6. Designed interactive visuals with slicers and a map

## Data Model

* Sales Data: fact table that holds orders, quantity, revenue and profit
* Date Calendar table: linked to the sales data using the order date
* Data table: linked to the sales data using a common key

## DAX Measures Used

* Total Revenue
* Total Gross Profit
* Gross Margin %
* Total Quantity
* Total Orders

Add your DAX code here, for example:

```
Total Revenue = SUM(Sales[Revenue])
Total Gross Profit = SUM(Sales[Revenue]) - SUM(Sales[Cost])
Gross Margin % = DIVIDE([Total Gross Profit], [Total Revenue])
Total Orders = DISTINCTCOUNT(Sales[Order ID])
```

Replace the table and column names above with the ones used in your own model.

## Dashboard Features

* Slicers for Quarter, Month, Product Category and Region
* KPI cards for revenue, gross profit, gross margin, quantity and orders
* Month wise revenue and profit trend
* Top 5 and Bottom 5 countries by revenue
* Sales channel comparison
* Product category by gross profit
* Map view of revenue by country

## Key Insights

* The United Kingdom and Germany are the top revenue markets with 74K and 70K
* Online Store is the strongest sales channel with about 40% share
* Hiking and Camping are the top product categories by gross profit

## Tools Used

* Power BI Desktop
* DAX
* Power Query
* Microsoft Excel

## Repository Structure

```
Executive_Sales_Dashboard_PowerBI/
    README.md
    Executive_Sales_Dashboard.pbix
    Data/
        Sales_Data.xlsx
    Images/
        Executive_Sale_Dashboard.png
```

## How to Use

1. Download the .pbix file from this repository
2. Open it in Power BI Desktop
3. Use the slicers to explore the data

## What I Learned

* How to build a proper data model in Power BI
* How to create a Date Calendar table and link it to the sales data
* How to write DAX measures that respond to filter context
* How to design a clean dashboard that is easy to read

## Author

Nayan Deepak Borse

Email: borsenayan5@gmail.com
