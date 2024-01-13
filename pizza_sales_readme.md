# Pizza Sales-Dashboard

## Problem Statement

This dashboard helps to provide insights and analysis on various aspects of pizza sales performance. The report starts with an overview dashboard that provides key
metrics such as total sales, average order value, and the number of
orders. The report then delves into detailed insights, with interactive
visualizations showcasing sales trends over time, top-selling pizzas.
Users can filter and drill down the data to gain a deeper
understanding of different aspects of sales performance. 

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

- Step 3 : It was observed that in none of the columns errors & empty values were present.
- Step 4 : New column is added  Order Day,Order Month,Total Order,Total Pizza sold,total revenue by using DAX function
- Step 5 : To display the daily trend, select Stacked column chart,Drag the "Order Day" to X-axix and "Total Order" to y-axix.
- Step 6 : For the monthly order report create a Area chat by selecting the "Order Month" to X-axix and the "Total Order" to Y-axix.  
- Step 7 : To determine the percentage of sales by size and category, create a stacked Donut chart. Place the "Pizza Size" or "Pizza Category" to legend section, and the "Total Revenue" column in the "Values" section.
- Step 8 : For the top 5 pizzas by revenue, quantity, and order, create a stacked bar chart and placed the "pizza name" to X-axix and "Total revenue" to Y-axix.
- Step 9 : For the worst 5 selling pizzas by revenue, quantity, and order, repeat the process in Step 8. 
          
