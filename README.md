# NSE-Stock-Data-Analysis


Project Overview
This project involves the analysis of historical closing price data for stocks listed on the National Stock Exchange (NSE) of India with a market capitalization exceeding 500 crore INR. The objective is to perform data preprocessing, exploratory data analysis (EDA), correlation analysis, time series decomposition, and anomaly detection to gain insights into stock market trends and behaviors.

Objectives
Data Preprocessing and Exploratory Data Analysis

Clean the dataset by handling missing values and outliers.
Perform basic statistical analysis on the stock prices and volumes.
Visualize the price trends of the first 10 stocks.
Correlation Analysis

Create a correlation matrix of stock returns.
Identify the most correlated pairs of stocks.
Visualize the correlations using a heatmap.
Time Series Decomposition

Choose one stock and perform time series decomposition.
Identify trend, seasonality, and residual components.
Interpret the results and their implications for trading.
Anomaly Detection

Develop a method to detect anomalous price movements.
Identify and list the top 5 most significant anomalies in the dataset.
Investigate and explain possible reasons for these anomalies.
Dataset
The dataset used in this project is titled "NSE Stock Historical Price Data (Market Cap > 500 Cr)." It contains the historical closing price data for all stocks listed on the NSE with a market capitalization exceeding 500 crore INR.

Methodology
Data Preprocessing and EDA
Handled missing values using forward fill method.
Identified and removed outliers using Z-scores.
Visualized the price trends of the first 10 stocks.
Correlation Analysis
Calculated daily returns for each stock.
Created a correlation matrix of stock returns.
Visualized correlations using a heatmap.
Time Series Decomposition
Performed time series decomposition on a chosen stock to identify trend, seasonality, and residual components.
Interpreted the results for potential trading insights.
Anomaly Detection
Applied Z-score method to detect anomalies in stock prices.
Listed and investigated the top 5 significant anomalies in the dataset.
Files in the Repository
NSE_Stock_Data_Analysis.ipynb: Jupyter Notebook containing the complete analysis and code.
data/NSE_Stock_Historical_Data.csv: Dataset used for the analysis.
README.md: This README file.
How to Run the Analysis
Clone the repository to your local machine:


bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook NSE_Stock_Data_Analysis.ipynb
Run the cells in the notebook to reproduce the analysis.

Conclusion
This project provides a comprehensive analysis of NSE stock data, highlighting key insights into market trends and stock behaviors. By performing data preprocessing, EDA, correlation analysis, time series decomposition, and anomaly detection, valuable patterns and anomalies were identified, offering potential implications for trading strategies.

Acknowledgments
Special thanks to the interviewers for providing this assignment and the opportunity to demonstrate my data analysis skills.

Feel free to modify this README file to better fit your specific project details and personal preferences.
