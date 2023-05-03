# Excel Sales Analysis Project

This project is an analysis of a sales dataset using Power Query and Power Pivot in Excel. The dataset includes a sales sheet with 6299 data and a dimension sheet. The sales sheet includes variables such as Order ID, Customer ID, Sales Person, Order Date, Order Priority, SKU, Order Quantity, Unit Sell Price, Discount, Shipping Amount, Ship Mode, Product Container, and Ship Date. The dimension sheet includes four tables - categorydim, customers, shipmodesort, and orderprioritydim.

## Dataset

The dataset is an Excel sheet containing sales data for a company. The sales sheet includes 6299 data and the dimension sheet includes four tables. Here is a brief overview of the tables:
Sales sheet: Includes variables such as Order ID, Customer ID, Sales Person, Order Date, Order Priority, SKU, Order Quantity, Unit Sell Price, Discount, Shipping Amount, Ship Mode, Product Container, and Ship Date.
1.	Categorydim: Includes SKU and Category.
2.	Customers: Includes Customer, State Code, and State.
3.	Shipmodesort: Includes Ship Mode and Sort Order.
4.	Orderprioritydim: Includes Order Priority and Sort Order.


## Analysis

The analysis was performed using Power Query and Power Pivot in Excel. Power Pivot was used to connect the different tables and create a data model. Here is a brief overview of the analysis:

1.	Sales amount by country: A calculated column was used to calculate the total sales amount for each country. This information was then used to create a map showing the sales amount by country. The average days it took to ship the products across countries was also calculated and displayed on the map.
2.	Sales by category and sales person: The sales amount in different categories was analyzed by each sales person. This information was displayed in a pivot table.
3.	Sales amount by year and quarter: The sales amount was analyzed by year and quarter for each sales person. The average shipping price for each item was also calculated and displayed in the pivot table.
4.	Slicer connection: Slicer connection was done to the pivot where it was required to filter the data.

## Dashboard

The dashboard was created using Power Query and Power Pivot in Excel. The auto update feature was enabled so that if a new Excel file is added to the folder, the dashboard will update automatically. The following features were included in the dashboard:

1.	Sales amount by country on a map
2.	Average days it took to ship the products across countries on the map
3.	Sales by category and sales person in a pivot table
4.	Sales amount by year and quarter for each sales person in a pivot table
5.	Average shipping price for each item in the pivot table

## Tools Used

I performed the analysis in Microsoft Excel and created the dashboard using Excel charts and graphs.

## Conclusion

In conclusion, this project was an analysis of a sales dataset using Power Query and Power Pivot in Excel. The dashboard included features such as sales amount by country on a map, sales by category and sales person in a pivot table, and sales amount by year and quarter for each sales person in a pivot table. The auto update feature was enabled so that if a new Excel file is added to the folder, the dashboard will update automatically.

