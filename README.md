# Infosys-Financial-Analysis-and-Quarterly-Forecasting-Using-Python
This analysis examines Infosys Ltd.’s quarterly financial performance from FY2021–FY2025. It includes data cleaning, growth rate calculation, profitability trend analysis, and time series forecasting to predict future revenues. Visualizations reveal key insights, helping stakeholders assess Infosys’s growth and financial stability.

# Methodology
1. Data Import & Preparation: The project starts by loading quarterly financials (revenue, operating income, net income, expenses, and profit margin) from a CSV file into a Pandas DataFrame. It then cleans data by standardizing column names, removing formatting issues, and handling missing values.
   
2. Feature Engineering: Indian financial year quarters are generated from date information for trend analysis. Numeric columns are validated and missing entries filled using forward and backward fill techniques.

3. Descriptive Analytics: Descriptive statistics summarize core financial metrics, and correlation analyses identify relationships between variables such as revenue, expenses, and margins

4. Growth Rate Analysis: Growth rates for revenue and net profits are calculated for each quarter to highlight business performance fluctuations. Interactive charts visualize underlying trends.

5. Forecasting: A linear regression model is fit to historical revenue data to forecast the next three quarters. Predicted results are presented alongside actuals using comparative plots.

6. Visualization: Both Matplotlib and Plotly are utilized for graphical representations of actual and forecasted values, facilitating quick understanding for business decision makers.

Forecasted Interactive Line Chart Preview
(https://github.com/Mariyan-260725/Infosys-Financial-Analysis-and-Quarterly-Forecasting-Using-Python/blob/main/Forecasted%20Interactive%20Line%20Chart.png)

