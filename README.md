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
  - (Optional) IBM Cloud Functions

---

## 🔧 Steps to Run the Project

### 1. IBM Cloud Setup
- Create a free [IBM Cloud Lite](https://www.ibm.com/cloud/free) account.
- Set up a Watson Studio project.
- Upload the dataset to IBM Cloud Object Storage.

### 2. Model Development
- Open the Jupyter Notebook in Watson Studio.
- Perform data preprocessing and feature engineering.
- Train the model using Random Forest, XGBoost, or Logistic Regression.
- Evaluate using Accuracy, F1-Score, and Confusion Matrix.

### 3. Model Deployment
- Deploy the trained model using IBM Watson Machine Learning.
- Expose it via a REST API for real-time predictions.

### 4. Prediction
- Use a Python script or frontend app to send project data and receive the predicted PMGSY scheme.



