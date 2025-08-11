# 💳 Credit Card Fraud Detection

**Credit Card Fraud Detection** is a Machine Learning project designed to detect fraudulent credit card transactions using anonymized real-world data. The project demonstrates how to handle imbalanced datasets, apply resampling techniques like SMOTE, and evaluate classification models for fraud detection.

This project showcases a full ML workflow using Scikit-learn and includes model export and manual prediction simulation for further integration or deployment.

---

## 🚀 Features

- Preprocessing of anonymized credit card transaction data  
- Feature scaling using `StandardScaler`  
- Handling class imbalance with:
  - ✅ Undersampling  
  - ✅ SMOTE (Synthetic Minority Oversampling Technique)  
- Classification models implemented:  
  - ✅ Logistic Regression  
  - ✅ Decision Tree Classifier  
- Model performance evaluation using Accuracy, Precision, Recall, and F1 Score  
- Final model exported using `joblib`  
- Manual prediction pipeline for transaction classification  

---

## 🧠 How It Works

1. Loads and cleans a real credit card transaction dataset  
2. Applies feature scaling and sampling techniques  
3. Trains classification models to detect fraud  
4. Evaluates performance on test data  
5. Saves the best model and performs live predictions on sample data  

---

## 📁 Dataset

The dataset is sourced from:

🔗 [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- Total transactions: 284,807  
- Fraudulent transactions: 492  
- Features: 28 anonymized PCA features (`V1–V28`), `Amount`, and `Time`  
- Target column: `Class` (`0` = Legitimate, `1` = Fraud)  

The credit card transaction dataset used in this project is large (over 140 MB) and **not included** in this repository.

You can **download the dataset for free from Kaggle**.

---

## 🧰 Tech Stack

- Python 3.13  
- Pandas  
- NumPy  
- Scikit-learn  
- imbalanced-learn (`SMOTE`)  
- Matplotlib & Seaborn (for visualization)  
- Joblib (for model serialization)  

---

## 🔍 Evaluation Metrics

Each model is evaluated using the following metrics:

- ✅ Accuracy  
- ✅ Precision  
- ✅ Recall  
- ✅ F1 Score  

These metrics are crucial for imbalanced classification problems like fraud detection.

---

## 👥 Contributors

This project was developed as part of a group academic project.

**Group Members:**

- Amil Gauri (Maintainer)  
- Ajay Chaurasiya  
- Vikas Pandit  
- Bhushan Salve  

> Project documented and maintained by **Amil Gauri** for public release.

---

## 📄 License

This project is open-source under the **MIT License**.  
You are free to use, modify, and distribute it with proper credit.

See the [LICENSE](LICENSE) file for full details.

---



