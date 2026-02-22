
📊 #Adventure Works Sales Data Analysis (2019)

📌 Project Overview

This project demonstrates an end-to-end Business Intelligence solution built using the Adventure Works 2019 dataset. The objective was to simulate a real-world business scenario — translating stakeholder requirements into a structured data model and interactive sales dashboard.

The solution includes dimensional modeling, SQL-based data warehouse design, and a Power BI report for KPI-driven analysis.

🏗️ Data Model

A Star Schema architecture was implemented:

Fact Table

FACT_InternetSales

Dimension Tables

DIM_Calendar

DIM_Customers

DIM_Products

Each dimension table contains descriptive attributes, while the fact table stores measurable sales transactions.

🛠️ Technologies Used

SQL (DDL scripts for schema creation)

Power BI (Dashboard & KPI reporting)

Excel (Sales Budget integration)

CSV datasets

Dimensional Data Modeling (Kimball methodology)

📊 Key Features

Revenue, Profit, and Order KPIs

Year-over-Year (YoY) & Monthly Trends

Budget vs Actual Sales Analysis

Product & Customer Performance Insights

Interactive filters and drill-down capability

📁 Repository Structure
DIM_Calendar.sql / .csv
DIM_Customers.sql / .csv
DIM_Products.sql / .csv
FACT_InternetSales.sql / .csv
SalesBudget.xlsx
Power BI Report (.pbix)
Business Requirement Documents
README.md
🎯 Business Objective

To enable data-driven decision-making by providing insights into:

Sales performance trends

Customer segmentation

Product profitability

Budget alignment vs actual revenue

🚀 Outcome

This project simulates a real-world BI lifecycle:

Business Request → Data Modeling → SQL Implementation → Dashboard Delivery
