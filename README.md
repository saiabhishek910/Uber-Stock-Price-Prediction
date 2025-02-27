# 🚀 Uber Stock Price Prediction

## 📌 Project Overview
This project aims to **predict Uber's stock price movement (Up/Down) using Machine Learning models**. We analyze historical stock data, extract key features, and apply classification algorithms to make predictions.

## 📊 Dataset
- **Source:** Kaggle  
- **Features Used:**
  - Open-Close Price Difference
  - High-Low Price Difference
  - Is Quarter End
  - Previous Day Close Price

## 🏗️ Tech Stack
- **Programming Language:** Python  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  

## 🧑‍💻 Models Implemented

| Model                | Training Accuracy | Testing Accuracy |
|----------------------|-----------------|-----------------|
| Logistic Regression | 52%             | 49%             |
| SVC (Poly Kernel)   | 53%             | 49%             |
| XGBoost             | **91%**         | **55%**         |

🔹 **XGBoost performed the best with 91% Training Accuracy and 55% Testing Accuracy.**  

## 📈 Performance Evaluation
- **Confusion Matrix**  
  - Helps visualize correct vs incorrect predictions  
- **Accuracy Score**  
  - Measures overall performance  
- **Classification Report**  
  - Includes Precision, Recall, and F1-score  

## 🖥️ Visualization
- 📌 **Confusion Matrix**
- 📌 **Stock Movement Predictions vs. Actual Values**
- 📌 **Feature Correlation Heatmap**

## 🔥 Key Findings
- The **XGBoost model outperformed Logistic Regression and SVC**, achieving the highest accuracy.

## 📜 License
This project is open-source under the MIT License.

## 💡 Author: Abhishek
If you found this useful, give it a ⭐ on GitHub!

