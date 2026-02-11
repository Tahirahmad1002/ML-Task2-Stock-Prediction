# Task 2: Short-Term Stock Price Prediction

## 📈 Project Overview
This project uses historical market data to predict the next day's closing price for a specific ticker (TSLA). It demonstrates the ability to handle time-series data, work with financial APIs, and evaluate regression models.

## 🛠️ Technical Workflow
1. **Data Acquisition**: Extracted 5 years of historical data using the `yfinance` API.
2. **Feature Engineering**: Created a **Target** variable by shifting the closing price by -1 day (Look-ahead).
3. **Data Splitting**: Implemented a **Time-Series Split** (80/20) to maintain chronological order and prevent data leakage.
4. **Modeling**: Trained and compared **Linear Regression** and **Random Forest Regressor**.

## 📊 Performance Results
* **Model Fit ($R^2$ Score)**: 95.74%
* **Mean Absolute Error (MAE)**: $6.80
* **Key Insight**: The Random Forest model effectively captured the non-linear trends and volatility of the stock price.

---
## 👤 Author
**Tahir Ahmad**
* **Role:** Machine Learning Intern at DeveloperHub Corporation
* **Interests:** flutter, ML, and Deep Learning.
* **Connect with me:** * [LinkedIn]([YOUR_LINKEDIN_URL](https://www.linkedin.com/in/tahir-ahmad-b03187296?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
    * [Email](mailto:tahirahmad1002@hmail.com)
