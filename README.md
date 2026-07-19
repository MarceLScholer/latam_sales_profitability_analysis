# LATAM Sales Profitability Analysis
### Exploratory Data Analysis | Python · Pandas · Matplotlib

This project analyzes sales profitability data across LATAM clients, products, 
and regions. The raw dataset required significant cleaning before analysis, 
making this project a realistic end-to-end EDA workflow.

## Project Workflow

1. **Data Loading** – Inspecting raw structure and handling metadata rows
2. **Data Cleansing** – Renaming columns, fixing data types, removing empty 
   columns and null rows
3. **Secondary Dataset** – Importing and merging Region and Product Type data
4. **Margin & Percent Calculation** – Computing profitability metrics per transaction
5. **Exploratory Analysis** – Aggregated visualizations by Client, Region, 
   Product Type and Period

## Key Findings
- Total Revenue of $1,785,279.55 and Margin of $830,026.42,	representing a overall profitability of 46.49%
- Chile and Canada lead in Revenue, however Canada shows the highest Margin, suggesting stronger profitability despite similar sales volumes.
- Jones & Sons leads in Revenue with 19.77%, followed by Breitenberg-Mosciski with 15.04%. However, Breitenberg-Mosciski takes the top position in Margin with 17.43%, while Jones & Sons drops to 12.69%, suggesting higher operational costs relative to its sales volume.
- QUOKAR leads with 20% of total Revenue among all product types, followed by CHOTUS and DONANY with a combined 28%. However, DONANY and CHOTUS together account for nearly a third of total Margin, while QUOKAR contributes only 11%, indicating lower profitability relative to its sales volume.
- Odd periods (1st, 3rd, 5th) consistently outperform even periods in both Revenue and Margin, with Period 1 leading overall results.

## Tools Used
- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Files
| File | Description |
|------|-------------|
| `sales_data_raw.csv` | Raw sales dataset (primary) |
| `sales_details_raw.csv` | Secondary dataset with Region and Product Type |
| `latam-sales-profitability-analysis.ipynb` | Full EDA notebook |

## Dataset
Sales transactions from multiple LATAM clients across different regions, 
product categories and billing periods. Data includes Revenue, Costs, 
Margin and Percent per transaction.
