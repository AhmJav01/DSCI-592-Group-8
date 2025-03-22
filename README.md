# DSCI-591-Group-8
This project explores the use of time series forecasting to analyze and predict stock price trends for four major automobile companies—Ford, Toyota, Volkswagen, and Tesla—each representing distinct global market sectors (American, Asian, European, and Electric). Motivated by shifting trade policies, political influence, and the global rise of electric vehicles, our goal is to evaluate how internal financial metrics and external factors (like tariffs, news events, and market sentiment) impact stock performance. We sourced historical stock data from Investing.com (2020–2025), focusing on key financial indicators such as open, high, low, close prices, trading volume, and percentage change.

The data acquisition and preprocessing phase involved cleaning and standardizing datasets across the four companies. We addressed missing values using median values, normalized volume units (e.g., converting 'K' and 'M' to numerical values), removed non-numeric characters from percentage changes, and ensured consistent datetime formatting. Feature engineering played a vital role, where we developed smoothed moving averages and captured time-based trends while reducing model redundancy. Exploratory Data Analysis (EDA) helped identify correlations, outliers, and trading patterns, while visualizations revealed major market events and behavioral anomalies affecting each company's stock price.

The next phase of this project will focus on builing predictive models with ARIMA for statistical time series forecasting as well as other additional machine learning techniques like Logistic Regression. Our next steps include validating models on 2025 Q1 data and potentially incorporating external data (e.g., news sentiment and social media trends) to improve long-term forecasting accuracy. Ultimately, this project aims to provide a holistic and explainable approach to stock trend analysis in the automobile industry, combining structured historical data with real-world macroeconomic and geopolitical insights.

This Repository inclued the following:
  3 Reports
    - Launch Report
    - Data Acquisition and Preprocessing Report
    - Exploratory Data Analytics Report

  4 Jupyter Notebook Files
    - Tesla Stock Code
    - Volkswagen Stock Code
    - Toyota Stock Code
    - Ford Stock Code

  2 Presentations & 2 Video Links
    - Pitch Presentation
      - Video Link: https://youtu.be/FaBld48_Wc8
    - Status Presentation
      - Video Link: https://youtu.be/Sept2j2sqps
