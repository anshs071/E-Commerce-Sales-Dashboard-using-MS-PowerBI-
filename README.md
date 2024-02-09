# E-Commerce Sales Dashboard

This repository contains a Power BI dashboard analyzing E-Commerce Sales data from CSV files.

## Data Sources

The dashboard connects to two CSV data files:

- orders.csv - Contains order header data like Order ID, Order Date, Customer Name, State, City. 

- details.csv - Contains order line details like Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode.
 
## Building our Dashboard 

### Started from transforming our data. 

- Created a new column AOV, calculated using the formula: AOV = [Amount]/[Quantity].
- Changed out Date column's datatype from text to date.

The key visualizations in the dashboard PDF include:

- Monthly profit/loss trends
- Profit by product sub-category 
- Order analysis by category
- Payment method mix  
- Total business KPI cards
- Sales by state 
- Top customers by spend
- Payment method profitability over time
- Quarter and state filters

## Insights

This enables insights like:

- Product performance and profitability
- Order trends and seasonality  
- Customer segmentation
- Payment method optimization
- Geographic differences

## Usage

To recreate:

1. Import the CSV data files into Power BI.
2. Build the visualizations.
3. Customize and extend analyses as needed.

This is a very small project. Hope you liked it!
