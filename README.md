# E-Commerce Sales Analysis — Google Sheets + Looker Studio

## Overview
An end-to-end sales analysis of the Kaggle Superstore dataset using Google Sheets for data cleaning and analysis, and Looker Studio for interactive dashboard creation.

## Tools Used
- Google Sheets — data cleaning, pivot tables, charts
- Looker Studio — interactive dashboard and filters
- Dataset: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Key Steps
1. Downloaded and imported the Superstore CSV into Google Sheets
2. Cleaned data — removed duplicates, fixed date formats, used TRIM()
3. Built 3 pivot tables — Category vs Sales/Profit, Region vs Sales, Monthly trend
4. Created charts — bar, pie, and line charts from pivot data
5. Connected Google Sheet to Looker Studio and built interactive dashboard
6. Added Region, Category, and Year filters/slicers

## Dashboard Highlights
- Total Sales: $2,297,200.86
- Total Profit: $286,397.02
- Technology is the highest-performing category
- West region leads in total sales
- Sales show an upward trend with seasonal peaks

## Key Insights
- Technology generates the highest sales and profit
- Furniture has the lowest profit margin despite high sales
- West region contributes 31.6% of total sales
- Sales peak in Q4 (November–December)

## Dashboard Preview
![Looker Studio Dashboard](dashboard/LookerStudio-Dashboard.pdf)

## Dataset
The cleaned dataset with corrected date formats (DD/MM/YYYY) is available in the `Data/` folder.
