# FraudShield-AI
# 🏦 FraudShield AI

**FraudShield AI** is an interactive Streamlit-based dashboard developed as part of the **PSB FinTech Hackathon** idea submission. The dashboard demonstrates how Artificial Intelligence and Machine Learning can assist banks in identifying potential mule accounts, visualizing fraud risk, and providing explainable insights for investigators.

> **Note:** This version is a demonstration dashboard created for the hackathon idea submission. The current risk score is generated using a rule-based scoring engine to showcase the user interface and workflow. In the full implementation, the dashboard will integrate a trained machine learning model for real-time mule account prediction.

---

## 🚀 Features

* 📂 Upload a CSV dataset containing banking account information.
* 📊 Mule Account Detection Table displaying:

  * Account ID
  * Mule Account Status
  * Risk Score
  * Risk Category
* 🚨 Top 10 Suspicious Accounts based on calculated risk score.
* 📈 Risk Category Distribution visualization.
* 📉 Most Important Fraud Drivers displayed as an interactive bar chart.
* 🔍 AI Explainable Fraud Detection for individual account analysis.
* 🧠 Real-Time Mule Account Investigation using feature sliders.
* 🎯 Interactive Risk Gauge showing fraud probability.
* 🚦 Alert Center with categorized risk levels.
* 🤖 AI Recommendation Engine suggesting actions based on the detected risk.

---

## 🛠️ Technology Stack

* **Frontend:** Streamlit
* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Interactive Visualizations:** Plotly
* **Version Control:** Git & GitHub


## 📊 Dashboard Workflow

1. Upload a banking transaction dataset.
2. Automatically calculate the fraud risk score for every account.
3. Classify accounts into:

   * 🟢 Low Risk
   * 🟠 Medium Risk
   * 🔴 High Risk
4. View suspicious accounts and fraud statistics.
5. Investigate individual accounts using the Explainable AI section.
6. Simulate new account feature values using the Real-Time Investigation Panel.
7. Receive recommended actions from the AI Recommendation Engine.

---

## 🔮 Future Improvements

* Integration with trained Machine Learning models (Random Forest, XGBoost, Gradient Boosting).
* SHAP-based Explainable AI.
* Real-time banking transaction monitoring.
* Network graph visualization for linked mule accounts.
* Automated PDF investigation reports.
* User authentication and role-based access.
* Cloud deployment with live prediction APIs.

---

## 🎯 Project Objective

The objective of FraudShield AI is to provide financial institutions with an intelligent fraud analysis platform capable of assisting investigators in identifying potential mule accounts quickly, improving fraud detection efficiency, and supporting informed decision-making through explainable AI.

---

## 👨‍💻 Developed For

**PSB FinTech Hackathon**

FraudShield AI is designed as a proof-of-concept demonstrating how AI-driven analytics and interactive dashboards can enhance financial fraud detection and investigation workflows.


