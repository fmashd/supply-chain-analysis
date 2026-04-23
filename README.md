# Supply Chain Data Analysis

## Project Overview
This project analyzes a supply chain dataset using Microsoft Excel. The aim was to clean the data, explore key business metrics, and identify important insights related to revenue, suppliers, locations, stock levels, costs, and product performance.

## Dataset
The dataset used in this project is:

- `supply_chain_data.csv`

It contains information on:
- Product type
- SKU
- Price
- Availability
- Number of products sold
- Revenue generated
- Customer demographics
- Stock levels
- Lead times
- Shipping times
- Shipping carriers
- Shipping costs
- Supplier name
- Location
- Production volumes
- Manufacturing lead time
- Manufacturing costs
- Inspection results
- Defect rates
- Transportation modes
- Routes
- Costs

## Tools Used
- Microsoft Excel
- CSV dataset

## Data Cleaning Process
The following cleaning steps were carried out in Excel:
- Imported the CSV file into Excel
- Converted the dataset into an Excel Table
- Checked and corrected number formats
- Reviewed columns for consistency
- Renamed confusing headers where necessary
- Applied filters to check for unusual values
- Reviewed low stock, high defect rates, and pending inspection records

## Analysis Performed
The following analysis was done in Excel:
- Created helper columns such as:
  - Revenue per Unit
  - Total Operating Cost
  - Estimated Profit
  - Risk Flag
- Built PivotTables to analyze:
  - Revenue by product type
  - Revenue by supplier
  - Revenue and cost by location
  - Shipping performance by transportation mode
- Created charts from PivotTables for visual analysis

## Key Findings
Some important findings from the analysis include:
- Cosmetics showed the highest average revenue among product categories
- Supplier 3 had strong revenue performance
- Mumbai recorded strong revenue with relatively lower manufacturing cost
- Some products had low stock levels and may need restocking
- Several items had high defect rates
- Many rows were marked as pending inspection, showing possible quality control delays

## Recommendations
Based on the analysis, the following actions are recommended:
- Restock items with very low stock levels
- Review suppliers with high defect rates
- Investigate products with failed or pending inspection results
- Monitor transportation methods with higher shipping costs
- Focus on high-performing product types and locations for better planning

## Project Files
Suggested project structure:

```text
supply-chain-analysis/
├─ data/
│  └─ supply_chain_data.csv
├─ analysis/
│  └─ supply_chain_analysis.xlsx
├─ images/
│  └─ charts.png
└─ README.md
