# 💳 Fraud Detection System (Machine Learning Based)

A complete end–to–end **Credit Card Fraud Detection System** using Machine Learning and Neural Networks.  
This project focuses on identifying fraudulent transactions from real-world imbalanced credit card datasets by applying preprocessing, feature scaling, oversampling, and multi-model classification.

---

## 🚀 Features

✔ Data preprocessing & feature engineering  
✔ Handling class imbalance using **SMOTE**  
✔ Model training using multiple ML algorithms  
✔ Deep learning model built using **TensorFlow/Keras**  
✔ Performance evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)  
✔ Visualization using Seaborn & Plotly  
✔ Streamlit deployment support  
✔ Model saving using **joblib**

---

## 🧠 Models Implemented

| Model | Type |
|------|------|
| Logistic Regression | Classifier |
| Random Forest | Ensemble |
| XGBoost | Gradient Boosted Trees |
| Isolation Forest | Anomaly Detection |
| Neural Network / LSTM | Deep Learning |

---

## 📊 Workflow

1. Load & explore dataset  
2. Apply scaling (`StandardScaler / MinMaxScaler`)  
3. Handle imbalance using **SMOTE**  
4. Train ML/DL models  
5. Evaluate using classification metrics  
6. Save best model using `joblib`  
7. (Optional) Deploy using **Streamlit + Ngrok**

---

## 🖥️ Run Project Locally

```bash
git clone https://github.com/<your-username>/fraud-detection-system.git
cd fraud-detection-system
pip install -r requirements.txt
