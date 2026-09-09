# TechMart Sales Performance Analysis

## Overview
Cleaned and analyzed a year of retail sales data for a fictional company (TechMart), identifying revenue trends, regional pricing inconsistencies, and product satisfaction patterns.

## Tools Used
Excel (data cleaning, pivot tables), Tableau Public (visualization)

## Business Questions
1. Which category generates the most revenue, and how does it trend monthly?
2. Are prices for the same product consistent across regions?
3. Which products have the highest and lowest customer ratings?

## Key Findings
- Electronics generates the highest revenue overall, though revenue fluctuates month to month with no clear seasonal trend.
- West region shows consistently lower average prices across nearly all products compared to other regions.
- Mechanical Keyboard has the highest average customer rating (~3.89), while Webcam HD has the lowest (~3.23).

## Dashboard
https://public.tableau.com/views/TechMartSalesAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Data Cleaning Steps
- Removed duplicate rows
- Standardized inconsistent product names and region labels
- Cleaned currency symbols from price column and converted to numeric
- Filled missing prices using average price per product
- Removed invalid negative quantity values
- Standardized inconsistent date formats
