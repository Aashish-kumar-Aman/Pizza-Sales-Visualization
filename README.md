Pizza-Sales-Dashboard

## Problem Statement

**KPI REQUIREMENT**
We need to analyze key indicators for our Pizza sales data to gain insights into our buisiness performance. Specially, we want to calculate the Following metrices:
**1.** **Total Revenue:** The sum of the total price of all pizza orders.
**2.** **Average Order Value:** The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
**3.** **Total Pizzas Sold:** The summ of all the quantities of pizzas sold.
**4.** **Total Orders:** The total number of orders placed.
**5.** **Average Pizza Per Order:** The average number of pizzas sold per order, calculated by dividing the total number of pizza sold by the total number of orders.

**CHARTS REQUIREMENT**
We need to visualize various aspects of our pizza sales data to gain insights and understand key trends. we have identified the following requirements for creating charts:
**1. Daily Trend for Total Orders:**
   create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctutations in order volumes on a daily basis.
**2. Monthly Trend for Total Orders:**
   Create a line chart that illustrates the hourly trend of total orders throughout the dy. This chart will allow us to identify peak hours or periods of high order activity.
**3. Percentage of Sales by Pizza Category:**
   create a pie chart that shows the distribution of sales accross different Pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.
**4. Percentage of sales by Pizza size:**
   Generate a pie chart that represents the percentage  of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.
**5. Total Pizzas Sold by Pizza Category:**
   Create a funnel chart that represents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.
**6. Top 5 Best Sellers by Revenue, Quantity and Total Orders:**
   Create a bar chart highlighting the top 5 best selling pizzas based on the Revenue, Quantity and Total Orders. This chart will help us identify the most popular pizza options.
**7. Bottom 5 Worst Sellers by Revenue, Quantity and Total Orders:**
   Create a bar chart highlighting the bottom 5 worst selling pizzas based on the Revenue, Quantity and Total Orders. This chart will help us identify the most underperforming less popular pizza options.

        
- Step 6 : New measure was created to find total revenue.

Following DAX expression was written for the same,
        
        Revenue = SUM('sales transactions'[norm_sales_amount])
        
A card visual was used to represent Revenue.

![Screenshot 2024-05-12 160115](https://github.com/Aashish-kumar-Aman/Sales-Insight-Report/assets/79306412/f7e999f7-ac69-4336-9f29-70d17c9aef42)

        
 - Step 7 : New measure was created to find total sales quantity
 
 Following DAX expression was written to find % of customers,
 
         Sales Qty = SUM('sales transactions'[sales_qty]) 129880)*100)
 
 A card visual was used to represent sales quantity.
 
 
![Screenshot 2024-05-12 160122](https://github.com/Aashish-kumar-Aman/Sales-Insight-Report/assets/79306412/f8e6bd63-64d8-4871-847a-e033da37abda)
 

 
 
# Snapshot of Report

![Screenshot 2024-05-12 160851](https://github.com/Aashish-kumar-Aman/Sales-Insight-Report/assets/79306412/c4017662-d956-47b3-a798-1124dfef6ef2)
 
 