# -Stock-Price-Movement-Using-Linear-Regression
📌 Project Overview
This project demonstrates a simple yet effective way to analyze and predict stock price behavior using Linear Regression. It helps visualize the stock market trend over time and gives an introductory understanding of how machine learning can be applied in stock price forecasting.

💡 Objective
Analyze the historical closing prices of a stock.
Train a Linear Regression model to learn the trend.
Predict stock prices based on date (time).
Visualize Actual vs Predicted stock prices using a line graph.
🛠️ Technologies Used
Python
Google Colab / Jupyter Notebook
Libraries:
yfinance – For downloading stock data
pandas – For data manipulation
matplotlib – For plotting graphs
sklearn.linear_model – For implementing Linear Regression
📥 Dataset
Stock data is fetched directly using the Yahoo Finance API via the yfinance library.
Example used: AAPL (Apple Inc.)
You can replace "AAPL" with any other stock symbol (e.g., "TSLA", "RELIANCE.NS").
📊 Methodology
Data Collection: Download stock data for a specific date range.
Preprocessing:
Convert Date to a numeric format using .toordinal() (Linear Regression requires numerical input).
Model Training:
Train a Linear Regression model using Date as the input (X) and Closing Price as the output (y).
Prediction:
Predict stock prices using the trained model.
Visualization:
Plot both actual and predicted stock prices for visual comparison.
📈 Graph Output
Blue Line → Actual Stock Prices
Red Line → Predicted Stock Prices (Linear Regression output)
📂 How to Run the Code
Open the project in Google Colab.
Run each cell step-by-step.
Modify the stock symbol if needed.
View the result graph.
📌 Key Concepts Explained
Linear Regression: A supervised machine learning algorithm used for predicting continuous values by learning a relationship between input and output.
toordinal(): Converts date into integer format so it can be used in regression models.
Predicting Trend: The model shows the overall upward or downward trend in stock prices.
📈 Example Use Case
Predicting stock prices or analyzing trends over a specific time period for making investment decisions, learning ML techniques, or academic projects.

🔁 Future Scope / Improvements
Add more features: Volume, Moving Averages, etc.
Use Multiple Linear Regression.
Try Polynomial Regression for non-linear trends.
Use advanced models like LSTM for better forecasting.
🙌 Author
Saksham Singh
B.Tech CSE (AIML)
