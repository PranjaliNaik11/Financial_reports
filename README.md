# Financial Reports Builder

This readme file provides guidance on building financial reports to assist a hedge fund manager. The reports are generated by analyzing income and balance sheet datasets. Both datasets contain common columns, including "Company," "comp_type," and "Year."

## Dataset Overview:

The datasets consist of the following columns:

- **Company:** The ticker name of the company.
- **comp_type:** The type of industry the company belongs to. It can be "tech" for technology companies, "fmcg" for fast-moving consumer goods companies, or "real_est" for real estate companies.
- **Year:** The year to which the company's financial information pertains.

## Report Objectives:

1. Calculate the leveraged ratio.
2. Calculate the profitability ratio.
3. Identify the company with the lowest profitability.
4. Identify the company with the highest profitability.
5. Create a scatter plot to understand the relationship between leveraged ratio and profitability ratio.

## Building the Financial Reports:

### Step 1: Data Preparation

Ensure that you have the following datasets:

- **Income Dataset:** Contains income statement information for various companies.
- **Balance Sheet Dataset:** Contains balance sheet information for the same set of companies.

### Step 2: Data Analysis:

1. **Calculate Leveraged Ratio:** The leveraged ratio can be calculated by dividing the company's total debt by its equity. Use the balance sheet dataset to obtain the total debt and equity for each company.
   
   Leveraged Ratio = Total Debt / Equity

2. **Calculate Profitability Ratio:** The profitability ratio can be calculated using different metrics such as Return on Assets (ROA) or Return on Equity (ROE). For simplicity, let's use ROA, which is calculated by dividing the company's net income by its total assets.

   Profitability Ratio = Net Income / Total Assets

3. **Identify Company with Lowest Profitability:** After calculating the profitability ratio for each company, identify the company with the lowest ratio. This can provide insights into underperforming companies.

4. **Identify Company with Highest Profitability:** Similarly, identify the company with the highest profitability ratio to identify top-performing companies.

### Step 3: Visualization

Create a scatter plot to visualize the relationship between the leveraged ratio and profitability ratio. Plot the leveraged ratio on the x-axis and the profitability ratio on the y-axis. This visualization can help in understanding how leverage impacts profitability across different companies.

## Conclusion

By following the steps outlined in this readme, you can build financial reports that assist hedge fund managers in analyzing companies based on their leveraged and profitability ratios. These reports provide valuable insights for investment decision-making and portfolio management.

Happy analyzing! 📊📈
