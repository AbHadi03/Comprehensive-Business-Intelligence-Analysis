# Comprehensive Business Intelligence Analysis for Strategic Decision-Making at Tata Group

This repository contains the deliverables for a Business Intelligence Project conducted for Tata Group. The project focuses on analyzing business scenarios, selecting and creating appropriate visuals, and communicating insights to senior management.

## Table of Contents
- [Project Description](#project-description)
- [Tasks Overview](#tasks-overview)
  - [Task 1: Framing the Business Scenario](#task-1-framing-the-business-scenario)
  - [Task 2: Choosing the Right Visuals](#task-2-choosing-the-right-visuals)
  - [Task 3: Creating Effective Visuals](#task-3-creating-effective-visuals)
  - [Task 4: Communicating Insights and Analysis](#task-4-communicating-insights-and-analysis)
- [Data Cleaning Process](#data-cleaning-process)
- [Tools Used](#tools-used)
- [How to Run the Project](#how-to-run-the-project)
- [Project Structure](#project-structure)
- [Contact Information](#contact-information)

## Project Description
This project involves performing a comprehensive business intelligence analysis to assist the CEO and CMO of Tata Group in making informed decisions. The analysis covers various aspects including revenue trends, top-performing regions and customers, and product demand insights.

## Tasks Overview

### Task 1: Framing the Business Scenario
Drafted a set of questions to anticipate the information needs of the CEO and CMO. These questions guide the development of the presentation and the subsequent analysis.

**Questions for the CEO:**
1. What are the seasonal trends in monthly revenue for 2011?
2. Which regions have the greatest demand for our products?
3. How can we forecast revenue for the next year based on current trends?
4. What are the key factors influencing the revenue trends?

**Questions for the CMO:**
1. Which are the top 10 countries generating the highest revenue, excluding the UK?
2. What is the quantity sold alongside the revenue generated in these top countries?
3. Who are our top 10 revenue-generating customers?
4. How can we ensure the satisfaction of our high-revenue customers?

### Task 2: Choosing the Right Visuals
Selected appropriate visualizations for the scenarios described in the questions from Task 1. This involved understanding the business requirements and choosing visuals that effectively convey the required information.

### Task 3: Creating Effective Visuals
Used Tableau to create the following visuals based on the cleaned data:
1. Time series of monthly revenue for 2011.
2. Top 10 countries generating the highest revenue, excluding the UK.
3. Top 10 customers by revenue.
4. Demand for products across different regions, excluding the UK.

### Task 4: Communicating Insights and Analysis
Developed a script and recorded a video presenting the findings to the CEO and CMO. The presentation covered the entire process from data cleaning to visual creation and provided insights based on the analysis.

## Data Cleaning Process
Performed the following data cleaning steps:
- Ensured quantity was not below 1 unit.
- Ensured unit price was not below $0.
- Used conditional formulas and data transformation methods to exclude erroneous data.

## Tools Used
- Tableau: For creating visualizations.
- Python: For data cleaning and preprocessing.
- Power BI: Alternative tool for creating visualizations (optional).

## How to Run the Project
1. Clone the repository.
2. Load the dataset and clean it using the provided Python scripts.
3. Open the Tableau or Power BI files to view the visualizations.
4. Watch the recorded presentation video to understand the insights and analysis.

## Project Structure
```
├── data
│   ├── raw_data.csv
│   ├── cleaned_data.csv
├── scripts
│   ├── data_cleaning.py
├── visuals
│   ├── time_series_revenue_2011.twbx
│   ├── top_10_countries_revenue.twbx
│   ├── top_10_customers_revenue.twbx
│   ├── product_demand_regions.twbx
├── presentation
│   ├── script.md
│   ├── presentation_video.mp4
├── README.md
```

## Contact Information
For any queries or further information, please contact Mohammad Hadi at dhukkahadi2001@gmail.com
