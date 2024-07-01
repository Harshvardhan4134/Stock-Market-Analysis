# Stock-Market-Analysis

```markdown
# 📈 Stock Market Analysis

Analyze the stock market performance of Apple (AAPL), Microsoft (MSFT), Amazon (AMZN), and Google (GOOGL) over the last three months using Python. This script fetches historical stock data, calculates moving averages, and visualizes stock prices and volatility.

## 📋 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🛠️ Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/Harshvardhan4134/stock-market-analysis.git
cd stock-market-analysis
pip install -r requirements.txt
```

Alternatively, you can manually install the required packages:

```bash
pip install pandas yfinance plotly numpy
```

## 🚀 Usage

Run the script to fetch data and generate visualizations:

```bash
python stock_analysis.py
```

## ✨ Features

- **Fetch Stock Data**: Retrieve historical stock data for the specified companies.
- **Data Preparation**: Concatenate and reset the index of dataframes.
- **Visualize Stock Prices**: Generate line and area charts to visualize closing prices.
- **Calculate Moving Averages**: Compute 10-day and 30-day moving averages.
- **Visualize Moving Averages**: Plot moving averages alongside closing prices.
- **Calculate Volatility**: Determine the rolling 10-day standard deviation of daily returns.
- **Visualize Volatility**: Plot volatility for each stock.
- **Correlation Analysis**: Analyze and visualize the correlation between Apple and Google.

## 📊 Visualizations

The script generates the following visualizations:

1. **Stock Market Performance for the Last 3 Months**: Line chart of closing prices for all companies.
2. **Stock Prices for Apple, Microsoft, Amazon, and Google**: Area charts of closing prices for each company.
3. **Moving Averages**: Line charts of closing prices with 10-day and 30-day moving averages.
4. **Volatility of All Companies**: Line chart of volatility for all companies.
5. **Correlation between Apple and Google**: Scatter plot with a trendline showing the correlation between Apple and Google closing prices.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions or suggestions, please contact [Harshvardhan](mailto:gharsha238@gmail.com).

```

Make sure to adjust the `git clone` URL, your name, and contact information accordingly. Also, include a `requirements.txt` file with the following content:

```txt
pandas
yfinance
plotly
numpy
```

