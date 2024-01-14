# Super_store_sales-Dashboard

## Problem Statement

The global super store faces several problem areas that need attention and improvement. These include inefficient sales by market, reliance on a few top customers, a need for profitability analysis of products, average delivery time above industry standards, high return order rates, and variations in sales performance by region. These issues hinder overall success and profitability. To address these problems, strategies must be devised to improve sales in low-performing markets, diversify the customer base, analyze profitable and loss products, streamline delivery processes, reduce return orders, and tailor strategies for regions with low sales. Rectifying these problem areas will maximize sales, profit margins, and customer satisfaction while identifying and resolving underlying issues.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : It was observed that in none of the columns errors & empty values were present.
- Step 4 :Create the dashboard
 To create the sum of segment and sum of sales by    market, drag the "segment" and "sales" fields onto the report canvas and choose the "Sum" aggregation for the "sales" field. Add "market" as a legend to show sales by market

To display the top 10 customers, drag the "customer" field onto the report canvas and use the "Top N" filter option to select the top 10 customers based on sales.
Follow a similar process to create visuals for the top 6 profit products and top 6 loss products using the "product category" and "profit" fields.
Customize each visualization by adjusting properties such as color, size, labels, and axis titles.
- Step 5 : Create a slicer
Drag the "Year" field onto the canvas and select the appropriate visual type like a "Tile".
