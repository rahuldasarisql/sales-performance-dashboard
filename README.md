# Sales Performance Dashboard — Power BI

## Business Problem
Sales team relied on static reports with no real-time visibility 
into regional performance, category trends, or profit margins — 
making it impossible to identify underperforming areas quickly.

## Solution
Built an interactive Power BI dashboard tracking key sales KPIs 
across regions and product categories with dynamic date filtering 
for period-over-period analysis.

## Dashboard KPIs
| Metric | Value |
|---|---|
| Total Sales | 144K |
| Total Profit | 23K |
| Profit Margin | 15.63% |
| Total Orders | 8 |

## Key Findings
- West region is the top performer across all sales periods
- Furniture dominates revenue at 51.39% of total sales
- Electronics contributes 39.58% — second highest category
- Clothing is the lowest segment at 9.03% — 
  signals potential for category strategy review
- Sales peaked around Jan 12 then dropped sharply — 
  identified as a trend requiring seasonal investigation

## Tools Used
- Power BI (Dashboard development, DAX measures)
- DAX (Profit Margin %, KPI calculations, 
  dynamic filtering logic)
- Power Query (Data cleaning and transformation)

## DAX Measures Built
- Profit Margin % = DIVIDE(Total Profit, Total Sales)
- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])

## Dashboard Pages
1. Full Overview — KPIs, trend line, regional and 
   category breakdown
2. Filtered View — Date slicer for dynamic period analysis
3. Category & Region Deep Dive — segment level comparison

## Screenshots
### Full Dashboard View
![Full Dashboard](https://github.com/user-attachments/assets/
f3b52a7f-9982-4204-bdce-89cdfc8685b7)

### Filtered View (Date Slicer Applied)
![Filtered View](https://github.com/user-attachments/assets/
53fbfcfc-fc2c-4ece-a5da-0fe0f5c9920e)

### Category & Region View
![Category & Region](https://github.com/user-attachments/assets/
e86f8c1d-669f-4edd-a345-1cab9df488a7)

## Project Files
- Sales_Performance_Dashboard.pbix

## Connect
- LinkedIn: https://www.linkedin.com/in/rahul-dasari-data
- GitHub: https://github.com/rahuldasarisql
