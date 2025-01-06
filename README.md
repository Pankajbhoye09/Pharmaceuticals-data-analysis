# Pharmaceutical Sales Analysis

This project analyzes raw sales data from a global pharmaceutical manufacturing company to extract meaningful insights and drive data-driven decision-making.





## Introduction

This project analyzes sales data from a leading global pharmaceutical manufacturing company. The company operates in various regions worldwide, including Germany and Poland, and collaborates with distributors to gather sales data at the retail level. This data, provided in CSV format, enables the company to gain valuable insights into its sales performance.

## Objectives

The project aims to provide in-depth data analysis to meet the following requirements:

| Requirement ID | Requirement Description                                                                                                                                                                                                                                                                        |
| :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DM-DA01-REQ-1  | A high-level overview of the company's overall sales performance by year, month, customer city, channel, and sub-channel, including top drug class, top drug, and top customer city by sales.                                                                                                               |
| DM-DA01-REQ-2  | A detailed overview of sales by distributors and products, top 5 products, customers, and cities, with sales numbers split by channels and sub-channels.                                                                                                                                          |
| DM-DA01-REQ-3  | A detailed report of sales by sales team, split by product and product class, including analysis of top sales managers, top sales representatives, and top products by sales team contributions, with the ability to filter/slice data by year and month. |

## Dataset

The dataset contains wholesale and retail sales data sourced from the company's distributors. It includes information on distributors, customers, products, sales quantities, prices, and sales representatives. The raw dataset (`pharma-data.csv`) can be downloaded from [here](https://drive.google.com/file/d/1npKF_C2tG5psY-at4wvpEgh6T-7KHxEZ/view?usp=share_link).

| Field            | Description                                |
| :--------------- | :----------------------------------------- |
| Distributor      | Name of wholesaler                        |
| Customer Name    | Name of customer                          |
| City             | Customer's city                           |
| Country          | Customer's country                        |
| Latitude         | Customer's Geo Latitude                    |
| Longitude        | Customer's Geo Longitude                   |
| Channel          | Class of buyer (Hospital, Pharmacy)      |
| Sub-channel      | Sector of the buyer (Government, Private) |
| Product Name     | Name of drug                              |
| Product Class    | Class of drug (Antibiotics, etc.)         |
| Quantity         | Quantity purchased                        |
| Price            | Price product was sold for                |
| Sales            | Amount made from sale                     |
| Month            | Month sale was made                       |
| Year             | Year sale was made                        |
| Name of Sales Rep | Name of the sales representative          |
| Manager          | Sales representative's manager            |
| Sales Team       | Sales representative's team               |

## Solution Approach

The project utilizes Power BI to create interactive dashboards and reports that address the defined objectives.

| Requirement ID | Solution ID          | Proposed Solution                                                                                                                                                             |
| :------------- | :-------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DM-DA01-REQ-1  | DM-DA01-SOL-1        | An "Executive Summary" dashboard provides a high-level overview of sales data with interactive visuals and year filtering.                                                         |
| DM-DA01-REQ-2  | DM-DA01-SOL-2        | A "Distributor & Customer Analysis" dashboard offers detailed insights into sales by distributors and customers, including top products, customers, and cities, and channel analysis. |
| DM-DA01-REQ-3  | DM-DA01-SOL-3        | A "Sales Team Performance" dashboard analyzes sales team performance, with drill-downs by product and product class, and filtering by year and month.                               |

### Data Exploration and Modeling

*   **Exploratory Data Analysis (EDA):**  The project utilizes pandas for initial data exploration to identify missing values, outliers, and data quality issues.
*   **Data Cleaning and Transformation:** Power Query Editor is used for data cleaning, transformation, and ensuring data quality.
*   **Data Model Creation:** A star schema data model is created in Power BI Desktop, separating dimensions and facts for efficient analysis.




## Credits

*   Dataset sourced from [Foresight BI](https://foresightbi.com.ng/practice-data/3-datasets-for-your-portfolio/)
