# 🤖 AI Stock Predictor & Financial Analyzer

An end-to-end Machine Learning web application that predicts stock prices, analyzes technical indicators, and performs sentiment analysis on the latest financial news.

## 🌟 Features
- **Price Prediction:** Uses Facebook's **Prophet** model for time-series forecasting.
- **Technical Indicators:** Calculates and visualizes **MA50** and **MA200** moving averages.
- **Sentiment Analysis:** Performs **NLP** on real-time news headlines via **TextBlob**.
- **Smart Recommendation:** Provides a "Buy/Sell/Hold" decision based on model output.
- **Interactive UI:** Built with **Gradio** for a seamless user experience.

## 🛠️ Tech Stack
- **Language:** Python
- **ML Framework:** Prophet
- **Data Source:** Yahoo Finance (yfinance)
- **NLP:** TextBlob
- **UI:** Gradio
- **Visualization:** Matplotlib & Pandas

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/shini74/AI-Stock-Predictor.git](https://github.com/shini74/AI-Stock-Predictor.git)

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   python app.py 
