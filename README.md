# RFM-Customer-Segmentation-in-Excel-Identifying-Top-Customers-and-Insights-for-Royal-Stores
This repository contains the documentation for the Royal Stores' RFM Analysis project. The full report and detailed documentation can be found on [Medium](https://medium.com/@remi.tajudeen/rfm-analysis-customer-segmentation-using-excel-ea1ace354c86).

## Project Overview
This project utilises RFM analysis in Microsoft Excel to segment Royal Stores' customers and identify the top three groups contributing the most to revenue.

## Objective
To optimise marketing spend by identifying high-value customer segments and understanding their purchase behavior.

## Dataset Description
The dataset was sourced from kaggle and it contains information on 2,240 customers with 29 columns. The dataset includes columns such as age, income, marital Status, education, number of web, catalog, and in-store purchases, amount spent on wines, fruits, meat, fish, sweets, and gold products.

## Project Methodology
Outlined below is a summary of the method used for the RFM analysis in Excel.

1. **Data Cleaning**: Removed missing values, fixed inconsistencies in categorical data, and handled outliers.
2. **Data Transformation**: Created new columns for age, discount status, total monetary value, purchase frequency, and revenue by channel.
3. **Feature Selection**: Identified and selected relevant columns needed for RFM analysis.
4. **Percentrank**: Used PERCENTRANK.INC to score recency (reversed), frequency, and monetary value. It was scaled 0 to 10.
5. **RFM Scoring**: Calculated the total RFM based on the percentrank values and created a new column to rank the RFM score using PERCENTRANK.INC.
6. **Customer Segmentation**: Segmented the customers using the lookup table created and the formula, VLOOKUP.
7. **Pivot Table for Customer Segment**: Created pivot tables for each segment to sumarize key statistics.
8. **Visualisation and Analysis**: The dashboard was created in Excel to explain each customer segment. 

## Key Insights
- **Top Customers (7.4%)** - This customer group has the highest average spend per purchase ($1,378), they are the company's most recent buyers, and have a high purchase frequency.
* **Loyal Customers (22%)** - This group is the largest and most valuable segment, 42% of total revenue comes from this segment. They frequently shop in-store and earn fairly high income.
+ **Growth Customers (16%)** - This segment is the second largest revenue driver, contributing 24%. Their purchasing frequency and spend is moderate with room for deeper engagement. There are opportunities to nurture this segments with loyalty offers and promotions.

## Recommendations
Based on the analysis, below are the recommendations for marketing strategies.

- **Prioritise personalised in-store experience**: Since all the customer segments have a prefernce for in-store shopping compared to online purchase, focus on improving store ambiance, customer service, and in-store promotions to increase engagement.
* **Targeted Premium Offerings**: Consider exclusive promotions or bundled offers that reflect the needs of the differnt customer segment.
+ **Retention and Engagemnet**: Use their recency and frequency data to create tailored marketing campaigns.

For a comprehensive overview of the project, analysis, and inisght, please refer to the documentation on [Medium](https://medium.com/@remi.tajudeen/rfm-analysis-customer-segmentation-using-excel-ea1ace354c86)





