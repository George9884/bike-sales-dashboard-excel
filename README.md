# Bike Sales Analysis Dashboard — Excel Data Project

Analyzed demographic data from 1,000 customers to identify purchasing behavior patterns for bike sales. Cleaned raw customer records, engineered custom demographic brackets, and built an interactive single-page dashboard featuring dynamic slicers and automated KPIs.


**Tools & Key Functions Used**

Microsoft Excel
Data Cleaning & Transformation, Pivot Tables, Pivot Charts, Slicers.

Text & Data Cleaning
Deduplication, string formatting (Find & Replace for marital status/gender abbreviations), currency standardization.

Custom Calculations
Nested IF logic for age segmentation:
=IF(Age>54, "Old", IF(Age>=31, "Middle Age", "Young"))

**Key Business Insights**

· Demographics & Income: Customers with higher average income are significantly more likely to purchase a bike across all regions.
· Age Bracket Target: Middle-aged adults (31–54) represent the vast majority of total bike purchases compared to young or elderly age groups.
· Commute Impact: Customers living within a 0–1 mile commute demonstrate the highest purchase conversion rates, declining rapidly as commute distance exceeds 5 miles.

**Dashboard Features & Layout**

KPI Metrics: 
Total Customers Analyzed, Purchase Conversion Rate, Average Income of Buyers.

Interactive Slicers: 
Filter seamlessly across Marital Status, Region, and Education.

**Visual Breakdown:**

· Clustered Column: Average Income per Purchase by Gender.
· Clustered Column: Customer Count by Age Bracket and Purchase Decision.
· Line Chart: Customer Commute Distance vs. Bike Purchases.

**Repository Structure**

· Bike-Sales-Dashboard.xlsx — Full Excel workbook containing raw data, cleaned working sheet, pivot tables, and interactive dashboard.

· dashboard.png — High-resolution preview screenshot of the final dashboard.


