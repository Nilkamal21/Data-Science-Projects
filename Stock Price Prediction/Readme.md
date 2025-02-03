# **Stock Price Prediction Using Machine Learning 📈**  

This project predicts the **closing stock price** of **Apple (AAPL)** using historical data fetched from `yfinance`. The model utilizes **Moving Averages (MA), Exponential Moving Averages (EMA), and Linear Regression** to forecast future stock prices.  

## **Project Overview**  
- **Data Source**: Fetched using `yfinance` (No need to upload a dataset manually)  
- **Features Used**:  
  - **7-day Moving Average (MA)**  
  - **7-day Exponential Moving Average (EMA)**  
- **Target Variable**: Closing Price (`Close_AAPL`)  
- **Machine Learning Model**: Linear Regression  
- **Performance Metrics**:  
  - **Mean Absolute Error (MAE)**: 2.05  
  - **Mean Squared Error (MSE)**: 6.39  
  - **R-squared Score (R²)**: 98.96%  

## **How to Run the Project? 🚀**  

### **Step 1: Install Dependencies**  
```bash
pip install yfinance pandas numpy scikit-learn matplotlib
```

### **Step 2: Run the Notebook or Script**  
- If using Jupyter Notebook:  
  ```bash
  jupyter notebook
  ```
  Then, open the `.ipynb` file and run all cells.  

- If using a Python script:  
  ```bash
  python stock_price_prediction.py
  ```

### **Step 3: View the Predictions**  
- The script will **fetch stock data, process it, train a model, and predict closing prices**.  
- The results are **visualized using Matplotlib**.  

## **Project Files**  
- 📜 **Stock Price Prediction.ipynb** → Jupyter Notebook with full code  
- 📄 **README.md** → Project description  
- 📄 **requirements.txt** → Dependencies list (optional)  

## **Results & Insights**  
- The model performs **exceptionally well (R² = 98.96%)**, meaning it explains most of the stock price variation.  
- Moving Averages and Exponential Moving Averages improve **predictive accuracy**.  
- The model can be extended to predict **other stock parameters like Open, High, Low, and Volume**.  

## **Future Improvements**  
✅ Adding more technical indicators (RSI, MACD)  
✅ Using advanced models like LSTM for time series forecasting  

---  
### **Author: Nilkamal Adhikari**  
📌 **Portfolio**: [GitHub Profile](https://github.com/Nilkamal21)  
📌 **LinkedIn**: [Nilkamal Adhikari](https://www.linkedin.com/in/nilkamal-adhikari-210592323)  

