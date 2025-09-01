This Jupyter Notebook is designed to analyze historical stock prices for multiple companies. It includes functionality to download stock data, calculate correlations, visualize trends, and perform advanced financial analyses such as rolling volatility and Bollinger Bands.

Features
1. Data Download
Downloads historical stock data for specified tickers using the yfinance library.
Saves the data to CSV files for future use.
2. Data Visualization
Plots closing prices for multiple stocks to visualize trends over time.
Generates heatmaps to show pairwise correlations between stock prices and returns.
3. Statistical Analysis
Calculates pairwise correlations between stock prices.
Computes rolling volatility for each stock to analyze risk over time.
Implements Bollinger Bands to identify price trends and potential trading signals.
4. Advanced Analysis
Performs year-over-year percentage change analysis for stock prices.
Calculates rolling correlations for returns and volatilities.
Conducts Engle–Granger cointegration tests to identify long-term relationships between stock pairs.
Creates animated rolling correlation heatmaps to visualize evolving relationships over time.
Libraries Used
yfinance: For downloading historical stock data.
pandas: For data manipulation and analysis.
numpy: For numerical computations.
matplotlib: For data visualization.
seaborn: For creating heatmaps.
statsmodels: For statistical tests like cointegration.
How to Use
Set Up: Ensure all required libraries are installed. You can install missing libraries using pip install.
Run the Notebook: Execute the cells in order to download data, perform analyses, and generate visualizations.
Modify Tickers: Update the tickers list in the notebook to analyze different stocks.
File Structure
Notebook: Contains all the code for data download, analysis, and visualization.
CSV Files: Each stock's historical data is saved as a CSV file in the same directory.
GIF Files: Animated rolling correlation heatmaps are saved as GIFs.
Customization
Modify the start and end dates in the data download section to analyze different time periods.
Adjust parameters like rolling window size and Bollinger Band settings to suit your analysis needs.
Example Tickers
META (Meta Platforms)
AAPL (Apple Inc.)
MSFT (Microsoft Corporation)
TSLA (Tesla, Inc.)
NVDA (NVIDIA Corporation)
INTC (Intel Corporation)
Outputs
Plots: Time series plots, heatmaps, and Bollinger Bands.
Statistics: Correlation coefficients, volatility measures, and cointegration test results.
Files: CSV files for downloaded data and GIFs for animated visualizations.
Notes
Ensure you have a stable internet connection to download stock data.
The notebook is designed for educational purposes and should not be used for financial decision-making without further validation.
Author
This notebook was developed to provide a comprehensive toolkit for stock price analysis. Feel free to modify and extend it for your specific needs.

You can copy and save this text as README.md in the same directory as your notebook. Let me know if you need further assistance!