🚧 PMGSY Scheme Classification Using Machine Learning
This project aims to automatically classify road and bridge construction projects under the Pradhan Mantri Gram Sadak Yojana (PMGSY) into their correct schemes (PMGSY-I, PMGSY-II, RCPLWEA) based on their physical and financial attributes. The solution leverages machine learning techniques and is deployed on IBM Cloud Lite.
📂 Project Overview
Traditional manual classification of PMGSY projects is time-consuming, error-prone, and unscalable as thousands of new projects are sanctioned each year. This system automates the process using historical project data to improve accuracy, transparency, and efficiency in monitoring and planning.

🧩 Solution Components
1️⃣ Data Collection
1. Source: AI Kosh PMGSY dataset
  -> Dataset Link
2. Data includes:
  -> Project location (State, District)
  -> Road length, road type, terrain
  -> Estimated cost
  -> Project duration and dates
  -> Whether the project includes a bridge
  -> Target scheme label
2️⃣ Model Development
Algorithms used:
  -> Random Forest
  -> XGBoost
  -> Logistic Regression (baseline)
Evaluation metrics:
  -> Accuracy
  -> F1-Score
  -> Confusion Matrix
3️⃣ Deployment on IBM Cloud Lite
  -> IBM Watson Studio: For training and experimentation
  -> IBM Cloud Object Storage: For storing datasets
  -> IBM Watson Machine Learning: For deploying the model as an API
  -> User Interface: Simple web app to input project details and get scheme predictions


