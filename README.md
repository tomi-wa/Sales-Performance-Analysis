**Sales Performance Analysis  **


This project provides a comprehensive sales performance analysis using the **Global Superstore Dataset**.  
The goal is to uncover insights related to shipping efficiency, discount impact, and regional sales performance using Excel for data cleaning, analysis, and visualization.


**Dataset Information**

- Source:Global Superstore Sales Dataset (Kaggle)  
- Rows: 9,994  
- Columns: 21 (trimmed to 10 for analysis)  
- Key Variables:
  - Order Date  
  - Ship Mode  
  - Region  
  - Category & Sub-Category  
  - Sales  
  - Discount  
  - Profit  

**Dataset Link**: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final


**Data Cleaning Summary**

- Removed unused columns to focus on business metrics.
- Verified dataset contained no missing values.
- Identified and removed 1 duplicate record.
- Detected outliers in the Discount column (0.6–0.8 range) and removed them.
- Confirmed Sales and Profit have no severe outliers.



**Research Questions**

1. How does shipping mode affect delivery time, sales, and profit?
2. What is the relationship between discount and profit margin?
3. Which regions generate the highest sales and profits?


**Key Insights**

1. Sales, Profit & Delivery Days by Ship Mode
- Standard Class had the most orders but longer delivery times.
- Same Day shipping delivered fastest but produced lower profit margins.
- First Class and Second Class provided a balance between speed and profitability.

2. Sales & Profit by Region
- West Region recorded the highest sales and profit.
- South Region showed moderate performance.
- Central Region slightly lagged behind in profit generation.

3. Relationship Between Discount & Profit
- Negative trend: Higher discounts lead to lower profits.
- Extreme discounts (0.6–0.8) consistently produced **negative profit margins.
- R² = 0.0347, indicating discounts affect profit but other factors also play a role.


**Conclusion**

- Shipping mode impacts profitability — faster modes improve delivery but may reduce profit.
- Excessive discounts significantly reduce profit without boosting sales enough to compensate.
- Regional analysis shows strong opportunities in the West region.



**Limitations**

- Dataset represents a single time period.
- Some categorical fields excluded for simplicity.
- Analysis focused on high-level insights.

**Recommendations**

- Re-evaluate discount thresholds to minimize profit loss.
- Improve delivery efficiency for Standard Class orders.
- Implement deeper time-series analysis in future stages.

** Project File**

The complete PDF report is included in this repository:
- STAGE 0_OLUWATOMIWA_ADELEKE_SALES_PERFORMANCE_ANALYSIS.pdf

**Tools Used**

  - Microsoft Excel
  - Data Cleaning  
  - Pivot Tables  
  - Charts & Visualizations  
  - Regression Analysis  

For questions or collaboration:

**Oluwatomiwa Adeleke
Data Analyst 
Email: oluwatomiwaadeleke@gmail.com ** 
 

### ⭐ If you find this project helpful, consider giving the repository a star!
