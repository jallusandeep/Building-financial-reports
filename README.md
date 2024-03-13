**Project Summary:**

This project involves analyzing financial data to compute profitability and leverage ratios for companies. The primary objective is to identify relationships between profitability and leverage, specifically focusing on different types of companies.

**Code Overview:**

- **Importing Libraries:** The code begins by importing necessary libraries such as NumPy, Pandas, and Seaborn for data manipulation and visualization.

- **Data Loading:** Financial data from balance sheets and income statements are read into Pandas DataFrames.

- **Merging DataFrames:** The income statement and balance sheet data are merged based on common columns (Year, company, comp_type) to create a consolidated DataFrame named `df_ratios`.

- **Profitability Ratios:** The code computes profitability ratios, specifically the gross margin ratio and the operating margin ratio. In this snippet, only the gross margin ratio is calculated.

- **Leverage Ratios:** Similarly, the code computes leverage ratios, including the debt-to-equity ratio and the equity multiplier ratio. Only the debt-to-equity ratio is calculated in this snippet.

- **Analysis:** The computed ratios are used to analyze the financial performance of companies. Pivot tables are utilized to identify the average profitability and leverage ratios across different company types.

- **Visualization:** Finally, the code generates a scatter plot to visualize the relationship between leverage and profitability for real estate companies.

**Summary Findings:**

- **Lowest Average Profitability:** Companies in the FMCG sector exhibit the lowest average profitability ratio.
- **Highest Average Leverage:** Real estate companies demonstrate the highest average leverage ratio.
- **Relationship Analysis:** A positive relationship is observed between leverage and profitability for real estate companies, indicating that higher leverage ratios may lead to higher profitability.

**Next Steps:**

This code snippet provides a foundation for further analysis and exploration of financial data. Additional analyses could involve examining trends over time, comparing different industries, or conducting regression analysis to quantify relationships between financial ratios.
