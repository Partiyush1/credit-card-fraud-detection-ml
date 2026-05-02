# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Fraud detection is a critical problem in the banking and financial sector because fraudulent transactions can cause huge financial losses.

The project uses multiple Machine Learning algorithms to classify whether a transaction is **Fraudulent** or **Normal** based on transaction features.

---

# 🎯 Objective

The main objective of this project is:

* Detect fraudulent credit card transactions accurately.
* Handle highly imbalanced transaction data.
* Compare multiple Machine Learning algorithms.
* Identify the best-performing model for fraud detection.

---

# 📂 Dataset Information

Dataset used:

* Credit Card Fraud Detection Dataset
* Total Records: **284,807** transactions
* Fraud Transactions: **492**
* Normal Transactions: **284,315**

### Dataset Features

The dataset contains:

* `V1` to `V28` → anonymized transaction features
* `Time` → transaction time
* `Amount` → transaction amount
* `Class` → target variable

  * `0 = Normal Transaction`
  * `1 = Fraud Transaction`

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Google Colab

---

# 🔄 Project Workflow

## 1️⃣ Data Collection

The dataset is loaded using Pandas from an online source.

## 2️⃣ Data Exploration

Performed:

* Dataset shape analysis
* Feature analysis
* Fraud vs Normal transaction comparison
* Visualization using graphs

## 3️⃣ Data Preprocessing

Steps performed:

* Feature scaling using `StandardScaler`
* Removed unnecessary columns
* Created scaled features:

  * `scaled_amount`
  * `scaled_time`

## 4️⃣ Handling Imbalanced Data

Since fraud transactions are very low compared to normal transactions, SMOTE was used to balance the dataset.

## 5️⃣ Model Training

The following models were trained:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest

## 6️⃣ Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve

---

# 📊 Data Visualization

The project includes:

* Fraud vs Normal Transaction Count Plot
* Transaction Amount Distribution
* Boxplot for Fraud vs Normal Amounts
* Correlation Heatmap
* Model Accuracy Comparison Graph
* ROC Curve

---

# 🤖 Best Performing Model

### ✅ Random Forest Classifier

### Performance:

* Accuracy: **99.95%**
* High fraud detection capability
* Better precision and recall compared to other models

---

# 📈 Model Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 97.45%   |
| KNN                 | 99.81%   |
| Decision Tree       | 99.78%   |
| Random Forest       | 99.95%   |

---

# 💡 Why SMOTE Was Used

The dataset was highly imbalanced.

Without balancing:

* Model may predict most transactions as normal.
* Fraud detection performance becomes poor.

SMOTE creates synthetic fraud samples to balance the dataset.

---

# 🔍 Sample Prediction

The trained model can predict whether a new transaction is:

* Fraud
* Normal

using transaction feature values.

---

# 🚀 Future Improvements

This project can be enhanced further by:

* Deploying as a web application
* Real-time fraud detection system
* Deep learning implementation
* Explainable AI integration
* Live transaction monitoring dashboard

---

# 📌 Applications

* Banking Systems
* Payment Gateways
* Financial Security Systems
* Fraud Prevention Platforms

---

# 🧠 Learning Outcomes

Through this project, I learned:

* Data preprocessing
* Handling imbalanced datasets
* Feature scaling
* Model training and evaluation
* Data visualization
* Fraud detection using Machine Learning

---

# 👨‍💻 Author

**Partiyush Thakur**
B.Tech CSE (AI/ML) Student
Chitkara University, Punjab

---

# ⭐ Conclusion

This project successfully detects fraudulent credit card transactions using Machine Learning techniques. After comparing multiple algorithms, Random Forest performed best and achieved excellent fraud detection accuracy.
