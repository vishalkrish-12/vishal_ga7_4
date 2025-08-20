Supply Chain Correlation Analysis
This repository contains a comprehensive correlation analysis of supply chain data following Excel best practices.
Contact Information
Email: 23ds2000044@ds.study.iitm.ac.in
Files Included
correlation.csv
Contains the correlation matrix values calculated from the supply chain dataset with the following variables:
⦁	Supplier_Lead_Time
⦁	Inventory_Levels
⦁	Order_Frequency
⦁	Delivery_Performance
⦁	Cost_Per_Unit
heatmap.png
Visual representation of the correlation matrix using Excel-style conditional formatting with Red-White-Green color scheme:
⦁	Red: Low/negative correlations (-1 to 0)
⦁	White: Neutral correlations (around 0)
⦁	Green: High/positive correlations (0 to 1)
Key Findings
The correlation analysis reveals several important relationships in the supply chain data:
1.	Strong Positive Correlations:
⦁	Supplier Lead Time & Cost Per Unit (0.960)
⦁	Order Frequency & Delivery Performance (0.838)
2.	Strong Negative Correlations:
⦁	Supplier Lead Time & Delivery Performance (-0.916)
⦁	Supplier Lead Time & Order Frequency (-0.895)
⦁	Delivery Performance & Cost Per Unit (-0.913)
⦁	Order Frequency & Cost Per Unit (-0.842)
3.	Moderate Correlations:
⦁	Supplier Lead Time & Inventory Levels (0.350)
⦁	Inventory Levels & Cost Per Unit (0.365)
Analysis Methodology
The correlation matrix was generated using Excel's Data Analysis ToolPak following these steps:
1.	Data imported into Excel
2.	Data → Data Analysis → Correlation
3.	All 5 data columns selected with "Labels in first row" checked
4.	Output generated to new worksheet
5.	Conditional formatting applied with Red-White-Green color palette
Image Specifications
⦁	Heatmap dimensions: 400x400 to 512x512 pixels
⦁	Color scheme: Red-White-Green (Excel conditional formatting style)
⦁	Format: PNG
