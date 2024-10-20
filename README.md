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


  
