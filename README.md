# Excel Sales Analytics Project

This project analyzes a sales dataset using Microsoft Excel and focuses on lookup functions, data cleaning, aggregation, PivotTables, and business-oriented analysis.

## Project Objectives

The project covers:

- Multi-step lookups across multiple sheets
- INDEX + MATCH
- VLOOKUP
- COUNTIF / COUNTIFS
- SUMIF / SUMIFS
- AVERAGEIFS
- Data quality checks
- Duplicate detection
- Broken foreign key checks
- Revenue analysis
- Sales rep performance analysis
- PivotTables
- Calculated fields
- Ranking and Top-N analysis
- TEXTJOIN
- Date-based analysis

## Workbook Sheets

- `Orders`
- `Customers`
- `Products`
- `Sales_Reps`
- `Targets`
- `Q1_Lookups`
- `Q2_Cleaning`
- `Q3_Aggregation`
- `Q4_Pivot`
- `Q5_Analysis`

## Key Analysis Performed

### Lookups
Used VLOOKUP and INDEX-MATCH to retrieve related data across Orders, Products, Sales_Reps, and Targets.

Examples include:

- Order → Product → Category
- Order → Sales Rep → Rep Name
- Rep → Team Lead → Team Lead Name
- Two-way target lookup using Rep ID and Month

### Data Cleaning

Performed checks for:

- Duplicate order IDs
- Leading/trailing whitespace
- Inconsistent city casing
- Missing customer references
- Discontinued product references
- Suspicious cancelled orders with high discounts

### Aggregation

Analyzed:

- Revenue by date range
- Revenue by city
- Revenue by customer segment
- Top performing sales representatives
- Actual revenue vs target performance

### PivotTable Analysis

Created PivotTables for:

- Monthly revenue
- Quarterly revenue
- Revenue ranking by sales representative
- Product performance
- Regional analysis
- Profit margin analysis

## Tools Used

- Microsoft Excel
- VLOOKUP
- INDEX
- MATCH
- SUMIFS
- COUNTIFS
- AVERAGEIFS
- SUMPRODUCT
- LARGE
- TEXTJOIN
- PivotTables
- Calculated Fields

## Key Learning

This project strengthened my ability to translate business questions into Excel formulas and structured analysis.

The main challenge was not just writing formulas, but identifying the correct lookup path, aggregation level, criteria, and relationship between multiple sheets.

## Project File

The completed Excel workbook is available in this repository:

`Excel_Minor_Project_Aditya_Shermale.xlsx`

## Author

Created as part of my Data Analytics learning journey.
