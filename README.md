# Super Store-Excel Dashboard

## RAW Data:
The raw dataset was sourced from Kaggle and includes:

-> Order-level data such as region, product category, sales, discounts, shipping dates, and profits

-> Time-series information across multiple years

## Clean Data
Before building the dashboard, I focused on thoroughly cleaning and preparing the dataset:

-> Removed duplicates to eliminate redundant entries

-> Filtered out blank or irrelevant rows

->Sorted the data chronologically by Order Date and by Region for better aggregation

-> Created a new column called Profit Status using Excel formulas:

If profit > 0 → marked as Profit

Else → marked as Loss

-> Applied Conditional Formatting to visually differentiate Profits vs. Losses

## Dashboard Highlights
-> Year-wise Sales and Profit trend using a combo chart.

-> Region-wise performance using column and pie charts.

-> Category-wise distribution using bar charts

-> Interactive slicers for Region, Category, and Order Year filtering

-> A Macro-powered "Refresh Dashboard" button to update all visuals in one click

-> Timeline and slicers to explore the data dynamically

