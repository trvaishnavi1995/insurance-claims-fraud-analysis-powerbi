# insurance-claims-fraud-analysis-powerbi
Insurance Claims Fraud Analysis using Excel and Power BI with DAX, Star Schema Modeling, and Interactive Dashboard.
# Insurance Claims Fraud Analysis – Power BI Project

## Project Overview
This project analyzes insurance claims data to detect fraud patterns, risk segments, and claim trends using Excel and Power BI.

The dashboard uses Power Query, Star Schema data modeling, DAX calculations, and interactive visualizations.

## Dataset
Source: Mendeley Data Repository  
Records: 1000 insurance claims  
Attributes: 40 columns including policy details, incident information, and claim amounts.

## Tools Used
- Excel
- Power BI
- Power Query
- DAX

## Data Modeling
A Star Schema model was implemented with:
- Fact Table: insurance_claims
- Dimension Table: Calendar

## Key DAX Calculations
- Fraud Rate %
- Total Claims
- Total Claim Amount
- Claims YTD
- City Rank using RANKX

## Dashboard Features
- KPI Cards
- Fraud Rate by State
- Claim Band Analysis
- Risk Category Distribution
- Top 5 Cities by Fraud Claims
- Decomposition Tree
- Drill-through analysis
- Gauge visualization for Fraud Rate

## Key Insights
- Fraud rate observed: 24.7%
- High claim amounts contribute most to financial exposure
- Certain cities show higher fraud concentration
- Risk segmentation helps identify high-risk claims

