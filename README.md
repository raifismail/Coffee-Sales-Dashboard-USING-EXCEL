# Coffee-Sales-Dashboard

## Project Overview

This project is a comprehensive analysis of coffee sales data, designed to showcase my data analysis skills. The project involves gathering, cleaning, and visualizing data from various sources to provide insights into coffee sales performance across different regions, customer segments, and product types.

I have built an interactive dashboard that allows users to explore sales trends, top-performing products, and key customers using slicers and timelines. This dashboard is part of my Data Analyst portfolio and demonstrates my expertise in data wrangling, analysis, and visualization.

# Business Task:
 Objective: Optimize coffee sales by identifying high-performing customer segments and regions, while improving product offerings and expanding into underperforming markets.

  - Increase total sales by 15% in the next quarter.

  - Identify key product trends and customer preferences to improve marketing and inventory strategies.

  - Expand into potential growth regions based on sales trends by country.

## Stakeholders:

  - Sales Managers: To set targets based on regional performance and high-growth areas.

  - Marketing Team: To design campaigns targeting high-value customer segments.

  - Inventory Managers: To optimize stock based on product demand.

  - Finance Team: For revenue tracking and budget forecasting.

## Data preparation Steps for analysis:

1. XLOOKUP Function
   - Used to gather specific data efficiently from related tables for orders and products.

2. INDEX MATCH
   - Employed for its flexibility in collecting product data. It ensured accurate data matching, which is critical for understanding sales performance.

3. Sales Column:
   - Calculated by multiplying unit price by quantity to derive total sales for each transaction.

4. Roast Type Column:
   - Applied an IF function to categorize coffee roast types, assigning full names such as "rob" = "robusta," "exc" = "excelsa," "ara" = "arabica," and "lib" = "librarica.
  
5. Date Formatting:
   - Standardized the date format to "05-sep-2019" for consistency and easier filtering.

6. Unit Conversion:
   - Converted product size to kilograms (kg) to make it easier for users to understand and compare sizes.
  
7. Currency Conversion:
   - Converted unit prices and sales figures to USD for consistent reporting across all regions.

8. Duplicate Check
   - Ensured data integrity by checking and removing duplicate entries


## visualization:
interactive excel dashboard , you will find it [here](https://github.com/raifismail/Coffee-Sales-Dashboard-USING-EXCEL/blob/93290923965cecd5262e065171c079e88830997b/NEW%20COFFEE%20PROJECT.xlsx)

![dashboard excel](https://github.com/raifismail/Coffee-Sales-Dashboard-USING-EXCEL/blob/8a4bbfcbc4028697fff057d565d09233b0534ae1/Screenshot%202024-10-20%20132130.png)

1. Total Sales Over Time (Line Chart):
    - Purpose: Track sales trends across months and quarters, identifying high-performing and underperforming periods.
  
    - Insight: Sales peak during specific months, indicating seasonal demand (e.g., holidays, promotional periods). The company should prepare by boosting inventory and 
      marketing during these months.

2. Sales by Country (Bar Chart):
    - Purpose: Compare sales across countries and identify which markets are driving the most revenue.
  
    - Insight: Some regions contribute significantly more sales, while others remain underdeveloped. This reveals opportunities for targeted marketing efforts in 
      underperforming regions and continued expansion in high-growth markets.

3. Top 5 Customers (Bar Chart):
    - Purpose: Highlight the top customers by revenue, helping to identify high-value accounts.
      
    - Insight: A small portion of customers contributes disproportionately to overall sales.

4. Slicers and Timeline:
    - Purpose: Provide dynamic filtering options to explore data by size, roast type, loyalty card status, and time periods.
  
    - Insight: Customer preferences can vary by region and loyalty status. For example, loyalty cardholders may prefer larger sizes or specific roast types.
  

## Insights and Recommendations:

1. Focus on Seasonal Trends:
   
   - Insight: Sales are not uniform throughout the year, peaking during specific months.
     
   - Recommendation: Align marketing campaigns, promotional events, and stock levels with these peak periods to maximize sales. Consider launching targeted campaigns during 
     low-sales months to even out performance.

2. Maximize Revenue from High-Value Customers:

   - Insight: A small segment of customers generates a significant portion of sales.
     
   - Recommendation: Offer exclusive benefits or incen#tives to these top customers, such as early access to new products or loyalty rewards, to ensure retention and 
     increase repeat purchases.
      
3. Market Expansion in Underperforming Regions:

   - Insight: Certain regions are underperforming in terms of sales.
     
   - Recommendation: Conduct market research to identify the barriers preventing higher sales in these regions. Tailor marketing campaigns to meet local preferences, and 
     consider adjusting pricing or introducing new product lines better suited to these markets.

4. Product Popularity by Size and Roast Type:

   - Insight: Sales patterns vary significantly by product size and roast type.
     
   - Recommendation: Adjust inventory levels to ensure adequate stock of popular product types, and consider phasing out low-demand options. Additionally, market campaigns 
     should emphasize the most popular sizes and roast types in each region.

## Key Takeaways:

   - Actionable Insights: The dashboard allows stakeholders to make data-driven decisions regarding sales strategies, customer engagement, and product offerings.
     
   - Dynamic Exploration: Interactive features make it easy to drill down into specific areas of interest, such as top products, customers, or regions.
     
   - Demonstrated Skills: This project showcases my ability to clean, analyze, and visualize data while providing real business value through actionable insights.

## How to Access the Project:

Download the Excel file from this repository [here](https://github.com/raifismail/Coffee-Sales-Dashboard-USING-EXCEL/blob/c3ba97c72eb440e04d58479185b39ec2fdebb5fb/coffeeOrdersData.xlsx)

Use the slicers and timeline to filter data as needed.


  
