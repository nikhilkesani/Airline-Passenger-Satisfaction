# ✈️ Airline Passenger Satisfaction Analysis Using Machine Learning

This project focuses on developing a machine learning-based classification system to predict airline passenger satisfaction using a large dataset of over 100,000 records. By evaluating various models and fine-tuning features, we aim to provide insights into key factors influencing passenger satisfaction and achieve high model accuracy.

---

## 📊 Project Overview

- **Objective**: Classify whether a passenger is satisfied or not based on various service and personal features.
- **Dataset**: 103,904 records with 23 features from a public airline passenger satisfaction dataset.
- **Best Model**: Random Forest  
- **Accuracy Achieved**: **96.34%**

---

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `scikit-learn` – Model building and evaluation  
  - `pandas`, `numpy` – Data preprocessing and transformation  
  - `matplotlib` – Data visualization  

---

## 📌 Key Features

- **Data Preprocessing**:  
  - Cleaned missing values  
  - Encoded categorical variables  
  - Performed feature scaling

- **Modeling & Evaluation**:  
  - Trained and compared models: Logistic Regression, Decision Trees, Random Forest, Neural Networks  
  - Evaluated using: Accuracy, Precision, Recall, F1-score, Cross-validation

- **Feature Engineering**:  
  - Applied permutation-based feature importance to identify impactful variables

---

## 📈 Results

- **Random Forest** achieved the highest accuracy of **96.34%**
- Identified key predictors of passenger satisfaction including in-flight service, seat comfort, and onboard Wi-Fi quality

---

## 🧪 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/airline-satisfaction-analysis.git
   cd airline-satisfaction-analysis
