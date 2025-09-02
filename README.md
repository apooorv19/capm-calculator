📈 CAPM Stock Return Calculator

Welcome! This is a simple web tool that helps you understand the risk and potential return of different stocks, like Tesla, Apple, and Google, using a popular financial formula called the Capital Asset Pricing Model (CAPM).
What's the Big Idea Here? 🤔

Imagine you're deciding between two cars for a race. One is a super-fast, unpredictable sports car, and the other is a reliable, steady sedan.

    The sports car might win big, but it's also more likely to spin out. (This is a high-risk stock).

    The sedan probably won't win, but it will finish the race safely. (This is a low-risk stock).

In the stock market, "risk" is about how wildly a stock's price swings up and down compared to the overall market. "Return" is the potential profit you could make.

This tool helps you measure that risk (we call it Beta) and then calculates the theoretical return you should expect for taking that risk.
How to Use the App 🖱️

It's as simple as 1-2-3!

    Choose Your Stocks: In the dropdown menu, select up to 4 stocks you're interested in.

    Select the Time Period: Choose how many years of past data you want to analyze (from 1 to 10 years).

    Read the Results: The app will automatically do the calculations and show you the results.

Understanding the Results 📊

The app gives you a few key pieces of information:
1. Price Charts

These graphs simply show you the historical price of the stocks you selected. The "Normalized" chart puts them all on the same starting line so you can easily compare their performance over time.
2. Calculated Beta Value

This is the most important number for understanding risk.

    Beta = 1.0: The stock moves almost exactly in line with the overall market (like the S&P 500).

    Beta > 1.0: The stock is more "volatile" than the market. It tends to go up more when the market goes up, and down more when the market goes down. (Our sports car).

    Beta < 1.0: The stock is less volatile than the market. It's more stable. (Our reliable sedan).

3. Calculated Return using CAPM

This table shows the theoretical annual return the CAPM formula suggests you should expect from a stock, given its Beta (its risk level).

Important Note: This is not a prediction of future profits! It's a financial model's estimate of the return that would be fair compensation for the amount of risk you are taking.
For the Tech-Savvy 💻

This app is built with Python and Streamlit.

    Data Sources: Stock data is sourced from Yahoo Finance (yfinance) and market data from the Federal Reserve Economic Data (pandas-datareader).

    Core Libraries: pandas for data manipulation, numpy for calculations, and plotly for interactive charts.

How to Run Locally

Want to run this on your own machine?

    Clone the repository:

    git clone [https://github.com/apooorv19/capm-calculator.git](https://github.com/apooorv19/capm-calculator/tree/main)
    cd capm-calculator

    Install the required libraries:

    pip install -r requirements.txt

    Run the Streamlit app:

    streamlit run streamlit_app.py

