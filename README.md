# Sales_Analytics
This project involves a detailed analysis of sales data, including information on orders, products, and geographical distribution. The main goal is to identify key trends, determine the most profitable product categories and regions, evaluate the effectiveness of sales channels, and analyze logistics performance.

## Key Analysis Steps
Data Loading and Initial Exploration: Loading and inspecting the three raw datasets (events.csv, products.csv, countries.csv).

### Data Preprocessing and Cleaning:

Missing Values: Missing values in the Country Code column (6.16%) in events and in geographical columns in countries were filled with the value Uknown. Missing values in Units Sold (0.15%) were filled with the mean value.
Type Conversion: Order Date and Ship Date columns were converted to datetime format.
Feature Engineering: A new metric, revenue, was calculated as Units Sold * Unit Price.
Analysis and Visualization: Segmented analysis of sales by categories, channels, and geographical location.

### Key Findings and Conclusions
Financial Metrics
Total Revenue: 1,704,623,436

Total Units Sold: 6,586,428 units.

Products and Categories
Top Categories by Revenue:

*  Office Supplies Household
*  Cosmetics
*   Meat
*   Baby Food

The main contributor to overall profit was the Office Supplies category.

Top 3 Categories by Order Volume: Office Supplies, Beverages, Personal Care.

Geographical Distribution
Regional Leader: The primary market is concentrated in Europe, which leads across all metrics. Southern Europe is particularly dominant.

Top 5 Countries by Revenue: Uknown, Czech Republic, Ukraine, Bosnia and Herzegovina, Macedonia.


Logistics (Delivery Time)
Longest Delivery Time: The Asia region.

Fastest Delivery Time: Northern Europe.

 ### Overall Conclusion and Recommendations
The business holds a strong position in Europe with profitable items, but its seasonal dependence puts it in a volatile state.

Recommendations:

Reduce seasonal dependence and pay close attention to sales channels.

Categories with high sales volume (e.g., Beverages, Personal Care) should increase their profitability.

The overall decline in sales leading up to 2017 was due to a decrease in sales of high-profit categories. The reason for this sharp drop in demand requires further investigation.
