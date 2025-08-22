# Customer Churn Analysis Dashboard
A comprehensive, interactive data visualization tool built to explore customer churn, identify trends, and uncover key drivers of customer attrition within a telecom company.

## Short Description / Purpose
This Customer Churn Analysis Dashboard is a Power BI report designed to help business leaders and analysts understand why customers are leaving. The dashboard focuses on highlighting key metrics and visuals related to churn demographics, service usage, payment methods, and contract types, providing data-driven insights to inform marketing campaigns and business strategy aimed at customer retention.

## Tech Stack
The dashboard was built using the following tools and technologies, as seen in the video:

💻 Power BI Desktop – The primary data visualization platform used for creating the report.

💻 Power Query – Utilized for data cleaning and transformation before loading it into the data model.

💻 SQL Server Management Studio (SSMS) – Used to run SQL queries for data loading and manipulation from the original data source.

## Data Source
Source: A Telecom Customer Churn Data Excel file.
This dataset contains customer information on demographics (gender, age), account details (tenure, contract type, payment method), services used (internet, online security, tech support), and churn status. This data was loaded into a Microsoft SQL Server database for robust data management and integrity.

## Features / Highlights
### Business Problem
The telecommunications industry faces high competition, and customer churn (when a customer stops using a service) is a major threat to profitability. Without a clear understanding of the factors leading to churn, companies cannot effectively create targeted retention strategies. This leads to lost revenue and increased costs for acquiring new customers.

### Goal of the Dashboard
The main goal is to deliver an interactive visual tool that:

Enables users to explore customer data and identify patterns in churn behavior.

Supports strategic decisions, such as where to focus marketing efforts to retain at-risk customers.

Provides clear insights into the demographics, services, and contract types most associated with churn.

### Walkthrough of Key Visuals
Key KPIs (Top Left): The dashboard's header features four cards displaying key metrics: total customers, total new joiners, total churn, and the overall churn rate.

Churn by Demographics: A donut chart visualizes churn distribution by gender, while a line and stacked column chart shows churn rates by age group.

Account & Services Analysis: A series of clustered bar charts and a matrix visual (with data bars) show churn rates by payment method, contract type, and customer tenure. This section also breaks down churn based on the specific services customers are subscribed to (e.g., internet service, online security, tech support).

Geographic Insights: A clustered bar chart displays the top five states with the highest churn rates, helping to pinpoint geographical problem areas.

Churn Distribution by Category: A clustered bar chart shows the total churn across various reasons, with a linked tooltip page that provides more detailed information on churn reasons.

Interactive Filters: Slicers are included to allow users to filter data by monthly charge range and marital status.

### Business Impact & Insights
Targeted Marketing: The dashboard allows marketing teams to identify specific customer segments (e.g., those on month-to-month contracts or a particular age group) most likely to churn, enabling highly targeted and effective retention campaigns.

Strategic Planning: Business leaders can use the insights on top churn drivers to improve service offerings, renegotiate contract terms, or enhance customer support for specific pain points.
## Screenshots/Demo
![Dahboard Preview](github.com/Ritika-piplani/Churn-Analysis/blob/main/Snapshot%20of%20Dashboard.png)
