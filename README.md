# 📈 Stock Price Prediction with LSTM (Amazon Stock)

This project predicts **Amazon (AMZN) stock prices** using a **Long Short-Term Memory (LSTM)** neural network.  
It demonstrates a full workflow from **data collection → preprocessing → visualization → model training → evaluation → saving the model**.  

---

## 🚀 Features
- Fetches **historical stock data** from Yahoo Finance.
- Performs **data preprocessing** (missing values, scaling, train-test split).
- Uses **LSTM** (sequential deep learning model) for time-series forecasting.
- Visualizes:
  - Stock price trends
  - Candlestick charts
  - Moving averages
  - Predictions vs. actual prices
- Saves the trained model (`AMZN.h5`) for reuse.

---

## 🛠 Tech Stack
- **Python**
- **Pandas / NumPy** → Data handling
- **Matplotlib / Plotly** → Visualization
- **Scikit-learn** → Scaling & preprocessing
- **Keras (TensorFlow backend)** → LSTM model
- **Yahoo Finance API (yfinance)** → Stock data

---

## 📂 Project Structure
📦 Stock_Price_Prediction
┣ 📜 Stock_Price_Prediction.ipynb # Main notebook
┣ 📜 AMZN.csv # Saved dataset
┣ 📜 AMZN.h5 # Trained LSTM model
┣ 📜 requirements.txt # Dependencies
┗ 📜 README.md # Project documentation

## 📊 Results

- **The LSTM model learns from past 100 days of stock prices to predict future trends.
- **Predictions are plotted against actual test data for evaluation.
- **Model is saved (AMZN.h5) for deployment or further fine-tuning.

- <img width="871" height="289" alt="Screenshot 2025-09-22 160645" src="https://github.com/user-attachments/assets/9230325e-a57c-4cf7-bacd-45e90fe5bbbc" />
- <img width="632" height="341" alt="Screenshot 2025-09-22 160745" src="https://github.com/user-attachments/assets/a514306a-ce8f-4083-8064-0211a19f0841" />
- <img width="618" height="327" alt="Screenshot 2025-09-22 160821" src="https://github.com/user-attachments/assets/20723b8f-1941-4258-bde0-59cf53572c9e" />
- <img width="488" height="164" alt="Screenshot 2025-09-22 160852" src="https://github.com/user-attachments/assets/04adff9b-63b1-40bb-9e2c-4e7ef8d117f7" />
- <img width="623" height="308" alt="Screenshot 2025-09-22 160914" src="https://github.com/user-attachments/assets/a023ddf8-c427-4175-b661-9441743de00b" />


