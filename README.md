# 🔍 SmartAudit: AI-Powered Fraud Detection System

A machine learning-powered system designed to detect fraudulent transactions in auditing workflows. It emphasizes intelligent feature engineering and rigorous evaluation metrics to minimize false negatives and enhance audit reliability.

---

## 🧠 Tech Stack

- **Python**
- **scikit-learn**
- **pandas**, **NumPy**
- **matplotlib**, **seaborn** (for data visualization)

---

## 🛠️ Process Overview

### 1. Data Preprocessing
- Loaded and cleaned the dataset
- Handled missing values and detected outliers
- Encoded categorical variables
- Scaled numerical features for better model performance

### 2. Feature Engineering
- Engineered features such as:
  - Transaction frequency
  - Time-of-day patterns
  - Distribution and magnitude of amounts

### 3. Model Development
- Built a **Random Forest Classifier**
- Performed **hyperparameter tuning**
- Split the dataset: 80% training, 20% testing

### 4. Model Evaluation
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC
- Applied **10-fold cross-validation** to ensure robustness

### 5. Results Interpretation
- Achieved **Recall: 1.00** — ensuring **zero false negatives**
- Balanced Precision and Recall — suitable for real-time fraud flagging

---

## 🚀 Future Enhancements

- Implement a **real-time API** using **FastAPI**
- Create interactive **dashboards using Power BI or Streamlit**
- Extend the model to handle **anomaly detection** for **automated internal audits**

---

## Installation

- git clone https://github.com/yourusername/SmartAudit-Fraud-Detection.git
- cd SmartAudit-Fraud-Detection
- pip install -r requirements.txt


---

## 📁 Project Structure

```bash
├── data/
│   └── transactions.csv
├── notebooks/
│   └── fraud_detection_analysis.ipynb
├── models/
│   └── random_forest_model.pkl
├── app/
│   └── api.py
├── requirements.txt
└── README.md
