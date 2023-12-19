# CoffeeShop_Analysis

### Table of contents:

-[Project overview](Project-Overview)

-[Data source](Data-Source)

-[Tool used](Tool-used)

-[Approaches used](Approaches-Used)

-[Findings](Findings)

-[Recommendations](Recommendations)

### Project overview:
Maven Roasters is a coffee shop chain with three locations in New York City. This project is to better understand the purchasing behavior and streamline operations of Maven Roasters. 

### Project aim:

To transform the data into a dynamic dashboard that franchise owners can use to identify patterns, trends and opportunities for the business.

### Data source:

The dataset was obtained from Maven Analytics. It is a collection of transactional data from Jan-Jun 2023.

### Tools used:

MS Excel is used for data preparation, data exploration and for dashboard building.

### Approaches used:

1. Data preparation for analysis: 
Familiarized with the data to understand basic things like number of transactions recorded, time of transaction, products and product categories sold. For this, the data was converted to a table format and used the filter option on the headers to get an understanding of each field.
Checked for null values and duplicates and no such cells were found.
Added a new column to calculate Revenue(unit_price*transaction_qty) and formatted as currency.
Added new columns to calculate Month and Day of Week (shown in the format of “Jan” and “Sun” respectively).
Added a new column to extract Hour from the transaction time.

2. Data exploration with pivot tables:
Pivot table 1: to show revenue by month.
Pivot table 2: to show the number of transactions by day of week.
Pivot table 3: to show the number of transactions by hour of day.
Pivot table 4: to show the number of transactions by product category, sorted descending by transactions.
Pivot table 5: to show the number of transactions and revenue by product type, sorted descending and filtered to the Top 15 by transactions.
Pivot table 6: to show the number of transactions by store location.
Pivot table 7: to show revenue by store location.
Pivot table 7: to show top 3 product categories by revenue.

3. Building a dynamic dashboard:
Adding pivot charts (Revenue by month - line chart,  transactions by day of week and hour of day - column charts, transactions by product category and revenue by store - bar chart, transactions by store - pie chart, top 3 product category by revenue - 3-D pie chart).
Assembled the charts into a rough dashboard in a new sheet in the same workbook.
Inserted slicer for store location and product category.
Adjusted formatting and alignment to get the final dashboard.
