Adventure Works Report

A business report using CSV data files including customer, sales, and product data; which has been synthesised and visualised using Power BI.

Project Overview:

This project is about a retail bike company that sells various types of products and performs a deep dive into their sales analytics, revenue forecasts and trends in customer behaviour.

Business Problem:

The business is looking through their data and wants to see where they perform best, in terms of location and products, and also how they are projected to perform in the future.
This analysis is important because it satisfies these demands, while offering further insight into the data at hand. The project supports decisions related: to which customers (and customer subgroups) purchase the goods the most, where purchases are coming from and the share of purchases from each location, product performance and how much revenue they generate for the company, as well as how each of these affect the other.

Project Objectives:

- Identify the highest spending customers
- Understand customer demographics affecting spending
- Locate which area garners the most customer revenue
- Decipher return rates and factors surrounding them
- Identify the highest-selling products
- Compare the monthly figures to the target numbers
- Forecast company performance
- Display and assess company KPIs

Data Sources:

Public dataset of unstructured sales, returns, customer data and more. 
![data files](https://github.com/user-attachments/assets/d3a58645-c9e5-4d5e-b2d0-41fcfbf754e3)
![cleaned data example](https://github.com/user-attachments/assets/4f264415-8cea-4247-98d5-8aa263ec9f47)


Tools and Technologies: 

Microsoft Excel for data cleaning.
Microsoft Power BI for further data manipulation, modelling and visualisation.

Data Preparation:

- After importing the CSV datasets to Power BI, I went through each table and transformed each row to ensure all data was clean and coherent.
- To do this, I: removed errors, assigned data types, promoted headers, added & combined columns using the extraction and parsing tools.
![cleaned data tables](https://github.com/user-attachments/assets/8d4f4080-12c2-4c2e-901a-19858c6d7a0b)


Some of these created other issues for me, especially with customer data, where some values had prefixes in front of the First Name, so I had to use the delimiter function in reverse to get the last name first before separating the prefix and first name. 
Another problem arose when merging queries. Some columns were common between tables, but the data wasn't always in the same format, so ensuring the formats were coherent was another issue I had, but I managed to overcome it when assessing the data, so that I could effectively model it as seen below:
![data modelling](https://github.com/user-attachments/assets/41951a9a-83c9-4718-bfde-15216519852a)

Analysis and Methodology:

The analysis focused on understanding sales trends, customer behaviour, and inventory performance to help the bike shop optimise its operations and boost revenue.
- Sales Trend Analysis: Time-series analysis was conducted on monthly sales data to identify seasonal patterns and peak sales periods. Area charts and pie charts visualised sales volume changes over time, highlighting growth opportunities and off-peak periods, as well as how different customer characteristics affected sales data.
- Product Performance: Gauges and area charts were used to display top-selling products and accessories. Custom DAX measures calculate revenue trends, performance relating to their targets and profit margins for each product category, helping prioritise inventory investment.
- Customer Segmentation: Using demographic and purchase frequency data, customers were segmented into groups such as occupation and income level. Cards, geospatial maps and tables enabled interactive exploration of buying patterns by age group and region.
- Dashboard Interactivity: Multiple slicers and drill-through actions were implemented to allow users to dynamically filter data by date range, product line, and customer segment, facilitating a user-driven exploration of critical business metrics.
Overall, this analytical approach combined data visualisation with advanced DAX formulae to deliver actionable insights tailored to the bike shop’s strategic goals.

Key Insights: 
![customer map](https://github.com/user-attachments/assets/10c7e05d-df74-4430-87d3-ab99b276d19f)
![customer detail](https://github.com/user-attachments/assets/fa210f01-a6d0-4ee6-b3b5-243fa7c650bf)
![product detail](https://github.com/user-attachments/assets/ccaa7d77-cbc5-4ec0-947c-f995777b3ceb)
![executive dashboard](https://github.com/user-attachments/assets/e04dddc4-ba4d-420b-bda6-fd791a377cf3)

*The original version, raw data and the PDF version are linked to this repository.* 
Press "view raw" to access the pbix and the csv files.

*Thank you for viewing!*

