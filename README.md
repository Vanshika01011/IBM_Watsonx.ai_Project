# 🚧 PMGSY Scheme Classification Using Machine Learning

This project aims to classify road and bridge construction projects under the **Pradhan Mantri Gram Sadak Yojana (PMGSY)** into their correct scheme (e.g., PMGSY-I, PMGSY-II, RCPLWEA) using machine learning. The goal is to support better infrastructure planning, transparency, and decision-making. The model is deployed using **IBM Cloud Lite** services.

---

## 📌 Problem Statement

Thousands of road and bridge projects under PMGSY need to be classified into different schemes. Currently, this is done manually, which is time-consuming and prone to errors. This project builds an ML-based solution to automate the classification using project data like location, road length, cost, and duration.

---

## 📂 Dataset

- **Source:** [AI Kosh PMGSY Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)
- **Features include:**
  - State and district
  - Road type and length
  - Estimated cost
  - Start and end date
  - Whether it's a bridge project
  - Target scheme label (PMGSY-I, PMGSY-II, RCPLWEA)

---

## 🧪 Technologies Used

- Python
  - Pandas, Scikit-learn, XGBoost
- IBM Cloud Lite
  - IBM Watson Studio
  - IBM Cloud Object Storage
  - IBM Watson Machine Learning

---
## 🚀 Model Development

### ✅ Algorithms Used
- **Random Forest**
- **XGBoost**
- **Logistic Regression** (baseline model)

### 📊 Evaluation Metrics
- **Accuracy**
- **F1-Score**
- **Confusion Matrix**

---
## ☁️ Deployment on IBM Cloud Lite

- **IBM Watson Studio**: Used for model training, testing, and experimentation in a Jupyter notebook environment.
- **IBM Cloud Object Storage**: Used to store and access datasets securely in the cloud.
- **IBM Watson Machine Learning**: Used to deploy the trained model as a RESTful API for real-time prediction.
- **IBM Cloud Functions (Optional)**: Can be used to automatically trigger predictions or workflows based on events.
- **User Interface**: A simple web application (optional) to input project details and receive predicted PMGSY scheme classifications from the deployed model.





