# Reliance Stock Analysis - Exploratory Data Analysis (EDA) Project

This project is an exploratory data analysis (EDA) on historical stock data for Reliance Industries. The objective is to analyze stock growth over time, trading volume trends, and monthly returns, giving insights into the stock’s performance and volatility.

## Project Structure

This project is organized into the following sections:

1. **Price Trend Over Time**
2. **Monthly Average Volume**
3. **Monthly Returns Analysis**

Each section provides visualizations and observations based on historical data to better understand Reliance's stock trends.

## Dataset

The dataset includes daily trading information for Reliance stock, such as:

- **Date**: Trading date
- **Open, High, Low, Close**: Daily prices
- **Volume**: Number of shares traded
- **Turnover**: Total traded value

The data is structured with multiple columns, and specific columns are used for each analysis.

### File: `reliance_data.xlsx`

Place the `reliance_data.xlsx` file in the same directory as the notebook or specify the path to it. The notebook will load this dataset to perform the analysis.

## Analysis Sections

### 1. Price Trend Over Time

In this section, we plot the **Close Price** over time to visualize the overall trend. This helps identify long-term patterns, periods of growth, and any significant drops or peaks in price.

- **Code**: We use Python’s `matplotlib` library to plot the closing prices against the dates.
- **Output**: A line chart showing the price movement over time.

### 2. Monthly Average Volume

We calculate the **Monthly Average Volume** to understand trading activity patterns. Monthly averages can reveal periods of increased trading, possibly due to news or economic events impacting investor interest.

- **Code**: We group data by month and calculate the average volume, then plot it over time.
- **Output**: A line chart showing monthly average trading volume.

### 3. Monthly Returns Analysis

Monthly returns indicate the percentage change in the closing price from the start to the end of each month. This measure helps analyze stock volatility and performance in short-term intervals.

- **Code**: We calculate monthly returns as the percentage change in closing prices from month to month and plot the trend.
- **Output**: A line chart showing monthly returns, helping identify periods of significant volatility or stability.

## How to Run

1. **Clone the Repository** (if applicable) or download the project files.
2. Place `reliance_data.xlsx` in the same directory as the notebook or specify the correct path in the code.
3. Open the Jupyter Notebook (or Kaggle notebook).
4. Run each cell sequentially to load the data, perform the analysis, and generate the plots.

## Dependencies

The following Python libraries are required:

- `pandas` – For data manipulation and analysis
- `matplotlib` – For plotting charts
- `numpy` – For numerical calculations (if needed)

Install these packages using:
```bash
pip install pandas matplotlib numpy
```

## Observations and Conclusion

This analysis provides insights into Reliance’s stock behavior over time, highlighting:

- **Price Trends**: Long-term upward trends, periodic spikes, or drops.
- **Volume Patterns**: Average trading volumes indicating investor interest.
- **Volatility**: Monthly returns reflect volatility and potential risk.

Understanding these trends can be beneficial for investors and analysts. Further analysis could include correlating stock prices with external economic indicators, calculating moving averages, or comparing trends across different stocks.

## License

This project is for educational purposes and is not a financial recommendation.

