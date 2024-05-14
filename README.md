# Car-Sales-Analysis

## Business Objective:
The objective of this project is to design and develop a dynamic and interactive Car Sales Dashboard to effectively track and analyze sales performance in our car dealership. The dashboard visualizes critical KPIs and provides insights to help us make informed decisions and identify growth opportunities.

---

## Problem Statements:

### KPI’s Requirement:
1) The dashboard should provide real-time insights into key performance indicators (KPIs) related to our sales data, including Year-to-Date (YTD) Total Sales, Month-to-Date (MTD) Total Sales, Year-over-Year (YOY) Growth in Total Sales, and more.
2) It should enable us to monitor our progress, understand sales trends, and compare current performance with previous periods.

### Charts Requirement:
1) The dashboard should include various charts to visualize sales data effectively, such as YTD Sales Weekly Trend, YTD Total Sales by Body Style, YTD Total Sales by Color, YTD Cars Sold by Dealer Region, and more.
2) These charts will provide a comprehensive overview of sales distribution, trends, and geographical sales performance.

---

## Key Features:

 **Dynamic Filters:** Users can filter the dashboard by date range, car model, body style, color, and dealer region to focus on specific segments of sales data.
 
 **Interactive Charts:** Charts are interactive and allow users to drill down for detailed insights by clicking on data points or using slicers.
 
 **Real-Time Report:** The dashboard provides real-time updates, ensuring that sales data is always current and reflects the latest transactions.
 
 **Detailed Grids:** In addition to charts, detailed grids are provided to view all relevant information for each car sale, including model, body style, color, sales amount, dealer region, and date.
 
 **Geographical Visualization:** Geographic data is visualized using map charts, allowing users to analyze sales distribution across different dealer regions.

 ---

 ## Approach:

Here's our approach for creating a powerful Car Sales Dashboard:

1) **Identify Metrics:**
Determine the essential metrics to track, such as total sales, average price, and cars sold.
Identify KPIs to measure sales performance, including Year-to-Date (YTD) and Month-to-Date (MTD) sales, year-over-year growth, and more.
2) **Data Acquisition:**
Collect comprehensive data on car sales, including sales volumes, prices, car models, body styles, colors, dealer regions, and dates of sale.
Ensure the data collected covers a significant period to provide meaningful insights into sales trends and patterns.
3) **Data Cleaning:**
Perform data cleaning to remove any missing or incomplete data and ensure consistency in data format.
Validate and verify the accuracy of the collected data to eliminate errors and inconsistencies.
4) **Data Modeling:**
Create a robust data model that structures the collected data for efficient analysis and visualization.
Define relationships between different data tables (e.g., sales data, car models, dealerships) to enable seamless integration and analysis.
Implement measures and calculated columns to derive additional insights and facilitate complex calculations within the data model.
5) **Design Layout:**
Create an intuitive and visually appealing layout for the dashboard, focusing on clear and concise presentation of data.
Organize the dashboard elements in a logical manner, with easy navigation and clear labels for each section.
6) **Data Visualization:**
Utilize a variety of charts, graphs, and tables to effectively visualize sales trends, distribution of sales across different parameters (e.g., body style, color), and other key insights.
Choose appropriate visualization types based on the nature of the data and the insights to be conveyed.
7) **DAX Queries:**
Develop DAX (Data Analysis Expressions) queries to calculate complex metrics and perform advanced data analysis.
Use DAX functions to calculate KPIs such as YTD sales, MTD sales, year-over-year growth, and more.
8) **Implement Interactivity:**
Incorporate interactive features such as filters, slicers, and drill-down capabilities to allow users to explore data and gain deeper insights.
Enable users to dynamically interact with the dashboard and customize views based on their specific requirements.
9) **Ensure Accessibility:**
Ensure the dashboard is accessible across various devices and platforms, including desktops, laptops, tablets, and mobile phones.
Optimize the dashboard layout and design for responsiveness and compatibility with different screen sizes and resolutions.

By following these steps, we aim to create a comprehensive and user-friendly Car Sales Dashboard that provides valuable insights into our sales performance and helps drive informed decision-making.

---

## Dashboard Overview

 ### KPI's Metrics
  
 1) **Sales KPI :** Track year-to-date (YTD) and month-to-date (MTD) total sales, analyze percentage year-over-year (YOY) growth in sales, and compare YTD sales with previous year's YTD sales
 
    ![Screenshot 2024-05-03 163556](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/fd085517-d4a3-429e-acbf-c31a03f5a0d7)
 
 2) **Avegrage Price KPI :** Track year-to-date (YTD) and month-to-date (MTD) Average Price, analyze percentage year-over-year (YOY) growth, and compare YTD Average Price with previous year's YTD sales Average Price
 
    ![Screenshot 2024-05-03 163620](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/2ed4c501-36e0-4c92-b3f5-8b5486bf4759)
 
 3) **Car Sold KPI :** Track year-to-date (YTD) and month-to-date (MTD) Car Sold, analyze percentage year-over-year (YOY) growth in car sold, and compare YTD car sold with previous year's YTD car sold
 
    ![Screenshot 2024-05-03 163637](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/ee23d7a7-93b3-42ca-a000-2ffe4a95f732)

 ### Charts 
1) **YTD Sales Weekly Trend :**
   
    ![Screenshot 2024-05-03 170120](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/ee87dddb-0381-4ab7-8bca-12c003aed1b0)

 2) **YTD Total Sales bY Body Style :**

    ![Screenshot 2024-05-03 170142](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/6c408121-dff3-44d5-89cc-eb91fa7a73b2)

 3) **YTD Total Sales by Color**

    ![Screenshot 2024-05-03 170204](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/a1fdacea-163e-41bc-ac5c-66d040e59baf)

 4) **YTD Car Sold by Dealer Region :**

    ![Screenshot 2024-05-03 170241](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/25f2e5ba-b3c7-451d-99cf-16077f7eb277)

 5) **Company Wise Sales Tend In Grid Form**

     ![Screenshot 2024-05-03 170306](https://github.com/Deepak-Sheokand/Car-Sales-Dashboard/assets/156662689/749ba0ff-6460-4ca1-8cdf-67def76141e1)

---

## Conclusion :
1) Year-to-Date (YTD) Total Sales amount to $371.2M, marking a $70.8M increase compared to the Previous Year-to-Date (PYTD) Total Sales, with a Year-over-Year (YOY) Growth in Total Sales of 23.59%.
2) The Year-to-Date (YTD) Average Price stands at $28.0K, showing a decrease of $0.22K compared to the Previous Year-to-Date (PYTD) Average Price, resulting in a YOY Growth in Average Price decrease of 0.79%.
3) Year-to-Date (YTD) Car Sold total to 13K units, indicating a $2.62K increase compared to the Previous Year-to-Date (PYTD) Car Sold, with a YOY Growth in Car Sold of 24.57%.
4) Analysis of the Year-to-Date (YTD) weekly Sales Trend reveals the highest sales generated in the 36th week of the year, amounting to $14.9M.
5) Examination of the Year-to-Date (YTD) Total Sales by Body Style highlights SUVs as the highest selling body style, while Hardtop body style cars contribute the least to sales.
6) White emerges as the most preferred car color, with the highest number of cars sold.
7) Sales distribution analysis based on dealer regions shows Austin as the region with the highest car sales, while Middletown records the least.
8) Chevrolet company's cars emerge as the best-selling, generating the highest revenue.

---

## Thank you for your attention and interest in my Car Sales Dashboard Report.

---

## Data Analyst

[**Deepak Sheokand**](https://www.linkedin.com/in/deepak-sheokand-0a0833272/)
