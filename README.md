🚀 Uber Stock Price Prediction

📌 Project Overview

This project aims to predict Uber's stock price movement (Up/Down) using Machine Learning models. We analyze historical stock data, extract key features, and apply classification algorithms to make predictions.

📊 Dataset

Source: Kaggle

Features Used:

Open-Close Price Difference

High-Low Price Difference

Is Quarter End

Previous Day Close Price

🏗️ Tech Stack

Programming Language: Python

Libraries Used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

🧑‍💻 Models Implemented

Model

Training Accuracy

Testing Accuracy

Logistic Regression

52%

49%

SVC (Poly Kernel)

53%

49%

XGBoost

91%

55%

🔹 XGBoost performed the best with 91% Testing Accuracy.

📈 Performance Evaluation

Confusion Matrix

Helps visualize correct vs. incorrect predictions

Accuracy Score

Measures overall performance

Classification Report

Includes Precision, Recall, and F1-score

🖥️ Visualization

Confusion Matrix

Stock Movement Predictions vs. Actual Values

Feature Correlation Heatmap

🔥 Key Findings

The XGBoost model outperformed Logistic Regression and SVC, achieving the highest accuracy.

Feature engineering improved model performance.

More advanced models like LSTMs can be explored for future improvements.

🛠️ How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/Uber-Stock-Prediction.git
cd Uber-Stock-Prediction

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook

jupyter notebook

(Optional) Deploy with Streamlit

streamlit run app.py

📌 Future Improvements

Use Deep Learning models (LSTMs, GRUs) for time series prediction.

Add technical indicators like RSI, MACD, and Bollinger Bands.

Deploy as a real-time stock price predictor using Streamlit.

📜 License

This project is open-source under the MIT License.

💡 Author: Abhishek

If you found this useful, give it a ⭐ on GitHub and connect with me on LinkedIn!
