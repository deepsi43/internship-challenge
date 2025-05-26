# AI/ML Internship Challenge – Tekly Studio

Welcome! This challenge is designed to assess your understanding of machine learning workflows and your ability to communicate your thought process clearly.

---

## 💻 Challenge Prompt

Build a simple ML model that predicts cryptocurrency or stock price movement (up or down) based on public historical price data.

You may use any public data source (e.g., CoinGecko API, Yahoo Finance API, Kaggle datasets, or CSV files). Your focus should be on:
- Feature selection
- Model choice (baseline is fine)
- Evaluation metrics
- Interpretability

---


## 📦 What to Include

- A Jupyter notebook or Python script with:
  - Data loading
  - EDA/feature engineering
  - Model training and evaluation
- A `README.md` summarizing:
  - What you built
  - Key features
  - Assumptions and limitations
  - What you’d do next with more time

---
## 🧠 Evaluation Criteria

- Clarity of code and structure
- Soundness of ML approach
- Communication and documentation



Stock PricePrediction
 Dataset Details: 
kaggle data : World Stock Prices
         The following attributes have been provided in the dataset include the everyday updated ie.,date of the stock prices, Open,High,Low,Close, Volume, Stock splits ,Dividends,Stock Splits,Brand_Name,Ticker,Industry_Tag ,the domain or industry like food, retail, ecommerce etc, Country,

It is a common technique to find the
closing price to see if the stock market ended up in profit or losses.


The data can be used to find/predict the opening, closing prices of stocks and the 
highest value of a given stock or the of the day.

We are solving a regression problem as we are trying to predict the stock prices.

Data Loading:
          We have  taken a kaggle dataset called World Stock Prices.We got the options either others while we preferred using the dataset direclty by downloading the file , we can also use it from kagglehub.

Used Pandas library for importing the data file.

Data preprocessing 
         Preprocesing steps include identifying the missing values either drop it based on the given values we have dropped the following columns Capital Gains,Stock Splits and use imputation techniques like mean(numerical),median or most frequent(categorical) as a strategy to fill the missing values and drop columns 
 
Exploratory data analysis -We plotted the following:
Date vs closing price
Boxplot
Weekday vs Closing price
Pie chart for brands
Brand_Name vs Opening Price

Feature Extraction
Onehot encoding

Model training:
We have trained the model using different ML Algorithms line Linear Regression,KNN and we also used ensemble methods like RandomForestRegressor.

Model Evalutaion:
After model training , we calculate the Metrics which Include MeanSquared Error and Mean ABsoulte Error.


- Creativity and problem-solving
