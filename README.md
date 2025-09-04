<h1 align="center">💳 Credit Card Fraud Detection 🚨</h1>

<p align="center">
  <b>🔍 Detecting fraudulent transactions using Machine Learning 🚀</b><br>
  Built with Logistic Regression & XGBoost | Handles Extreme Class Imbalance with SMOTE  
</p>

---

## 📂 Dataset  
📌 **Source:** Kaggle – *Credit Card Fraud Detection*  
📊 **Total Records:** `284,807`  
⚠️ **Fraud Cases:** `492` (≈ 0.172%)  

🔑 **Features:**  
- `V1–V28`: PCA-transformed components 🔐  
- `Time`: Seconds elapsed since first transaction ⏳  
- `Amount`: Transaction value 💰  
- `Class`: Target ( `0 = Non-Fraud` ✅ | `1 = Fraud` ❌ )  

---

## 📊 Project Workflow  

<div align="center">

| Step | Description |
|------|-------------|
| 🧪 **EDA** | Imbalance Visualization, Correlation Matrix, Trends |
| ⚙ **Preprocessing** | RobustScaler (Time & Amount), SMOTE Balancing |
| 🤖 **Modeling** | Logistic Regression ⚡ & XGBoost 🚀 |
| 📈 **Evaluation** | Confusion Matrix, Precision, Recall, F1, PR-AUC, ROC-AUC |

</div>

---

## 🚀 Tech Stack  

<p align="center">
  <img src="https://img.shields.io/badge/Python-🐍-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/pandas-📊-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/numpy-🔢-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/scikit--learn-🤖-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/XGBoost-🌲-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/imbalanced--learn-⚖️-purple?style=for-the-badge"/>
</p>

---

## ✅ Key Results  

- 🔼 **Recall & F1-score improved** with SMOTE  
- 🥇 **XGBoost** outperformed Logistic Regression on imbalanced data  
- 🎯 **PR AUC** captured fraud detection ability despite imbalance  

<p align="center">
  <img src="https://media.giphy.com/media/26BoCVdjSJOWH9l6E/giphy.gif" width="300"/>
</p>

---

## 💻 Run the Project  

```bash
# 1️⃣ Clone the repository
git clone https://github.com/HimaniMahajan27/Credit_card_fraud_detection.git  

# 2️⃣ Navigate into the project folder
cd credit-card-fraud-detection  

# 3️⃣ Install dependencies
pip install -r requirements.txt  

# 4️⃣ Launch Jupyter Notebook
jupyter notebook Credit_Card_Fraud_Detection.ipynb  
