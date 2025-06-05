# DSCI-592-Group-8
This project explores the use of time series forecasting to analyze and predict stock price trends for four major automobile companies—Ford, Toyota, Volkswagen, and Tesla—each representing distinct global market sectors (American, Asian, European, and Electric). Motivated by shifting trade policies, political influence, and the global rise of electric vehicles, our goal is to evaluate how internal financial metrics and external factors (like tariffs, news events, and market sentiment) impact stock performance. We sourced historical stock data from Investing.com (2020–2025), focusing on key financial indicators such as open, high, low, close prices, trading volume, and percentage change.

The data acquisition and preprocessing phase involved cleaning and standardizing datasets across the four companies. We addressed missing values using median values, normalized volume units (e.g., converting 'K' and 'M' to numerical values), removed non-numeric characters from percentage changes, and ensured consistent datetime formatting. Feature engineering played a vital role, where we developed smoothed moving averages and captured time-based trends while reducing model redundancy. Exploratory Data Analysis (EDA) helped identify correlations, outliers, and trading patterns, while visualizations revealed major market events and behavioral anomalies affecting each company's stock price.

We used four algorithms/ models to create our time series forecast models; ARIMA, Prophet, XGBoost, and LTSM to see which method was the best at predicting stock prices. Each model was selected to test different methods used in time series forecasting, and all models were evaluated using RMSE (Root Mean Squared Error) and MAPE (Mean Absolute Percentage Error). Across all companies, we found little to no seasonality or patterns in stock prices over a five-year period. While all companies did show a spike in stock price in late 2021/ early 2022 there were very little overall trends across companies. XGBoost gave the most accurate predictions, as the model resulted in the lowest RMSE and MAPE scores. LSTM models also worked well, followed by Prophet and then ARIMA. The low seasonality and non-linearity were the major factors in determining which models would perform better than other, with XGBoost and LSTM having shown to be more equipped to handle irregular data as opposed to more traditional methods such as ARIMA and Prophet. 



This Repository inclued the following:<br>
<br>
  **Reports<br>**
    1. Launch Report (591) <br>
    2. Data Acquisition and Preprocessing Report<br>
    3. Exploratory Data Analytics Report<br>
    4. Final Report (592) <br>
    <br>
  **Jupyter Notebook Files<br>**
    1. Tesla Stock Code Data Analysis & Acquisition (591) <br>
    2. Volkswagen Stock Code Analysis & Acquisition (591) br>
    3. Toyota Stock Code Analysis & Acquisition (591) <br>
    4. Ford Stock Code Analysis & Acquisition (591) <br>
    5. Tesla Stock Code Prediction Model & Evaluation (592) <br>
    6. Volkswagen Stock Code Prediction Model & Evaluation (592) br>
    7. Toyota Stock Code Prediction Model & Evaluation (592) <br>
    8. Ford Stock Code Prediction Model & Evaluation (592) <br>
<br>

