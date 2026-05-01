# VENDMAT PYTHON ANALYSIS

## PROJECT OVERVIEW
This project analyzes a food ordering dataset (Vendmat) using Python to understand customer behavior, sales performance, and revenue patterns across multiple tech parks.

## OBJECTIVE
To explore ordering trends, identify high-performing items and locations, and generate business insights using data analysis and visualization.

## DATA CLEANING
- Converted date column to datetime format  
- Handled missing values in rating column using mean imputation  
- Checked for duplicate records (none found)  
- Validated data for inconsistencies (no negative prices or invalid ratings)  
- Standardized column names to lowercase  

## FEATURE ENGINEERING
- Extracted day of the week from date column  
- Created time-based features for analysis  

## KEY ANALYSIS
- Total orders, total revenue, and average order value (AOV)  
- Orders and revenue by tech park  
- Orders distribution by shift and day  
- Top-selling and highest revenue-generating items  
- Revenue contribution (%) by each tech park  
- Identification of repeat customers  
- Top-performing items within each tech park  

## VISUALIZATION
- Bar charts for revenue and orders by tech park  
- Orders by shift and day  
- Top 10 items analysis  
- Revenue contribution visualization  
- Heatmap (day vs shift analysis)  

## TOOLS USED
- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  

## KEY INSIGHTS
- Lunch generates the highest number of orders and revenue  
- Friday is the peak demand day, while Monday has the lowest activity  
- RMZ Azure Hebbal contributes the highest revenue (~35%)  
- High-protein items generate higher revenue despite fewer orders  
- Repeat customers significantly contribute to overall revenue  

## BUSINESS RECOMMENDATIONS
- Increase stock and operations during lunch hours  
- Introduce promotions on low-demand days (Monday)  
- Focus on high-revenue items  
- Retain repeat customers with loyalty programs  
