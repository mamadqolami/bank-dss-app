# 💼 Bank Direct Marketing DSS (Decision Support System)

A professional and interactive web-based Decision Support System (DSS) for targeted bank marketing campaigns, leveraging advanced machine learning ensemble models and interpretable AI (SHAP).  
This app helps marketing teams to upload customer data, select or ensemble multiple predictive models, and identify the most promising clients for a direct marketing campaign, along with actionable feature-level explanations.

---

## 🚀 Live App

👉 [Click here to access the Online DSS App](https://bank-dss-app-h6hv27fvhj29qphnznvk6n.streamlit.app)  
*(Replace with your real link after deployment)*

---

## 📝 Project Overview

This project implements a full pipeline for **imbalanced customer classification** in bank direct marketing, including:
- Advanced data preprocessing, outlier removal, and feature engineering
- Application of oversampling methods (SMOTE, ADASYN) to address class imbalance
- Training and hyperparameter optimization of multiple machine learning models (Logistic Regression, LDA, KNN, Decision Tree, Random Forest, XGBoost, LightGBM, MLP)
- Ensemble learning (Voting) for robust prediction
- Interpretability using SHAP for model explanations
- Professional, user-friendly dashboard (Streamlit) for campaign decision support

---

## ⚙️ How to Use

1. **Upload Data:**  
   Upload your prepared feature set (`X_test.csv`) via the app interface.
2. **Select Model & Threshold:**  
   Choose between ensemble voting or any single model. Adjust the prediction threshold for campaign targeting.
3. **Results & Export:**  
   Instantly see predicted probabilities, class assignments, and download the results.
4. **Interpretability:**  
   For each prediction, see the top contributing features using SHAP values (in Voting mode).
5. **No True Labels Required:**  
   The app is designed for real-world use where true responses are unknown.

---

## 📦 How to Run Locally

1. **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
    cd YOUR-REPO
    ```
2. **Install requirements:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Add your trained models (.pkl) and data files (`X_test.csv`) to the root or `models/` and `data/` folders.**
4. **Run the app:**
    ```bash
    streamlit run app.py
    ```

---

## ✨ Features

- **Multiple model support:**  
  Easily switch between ensemble and single models.
- **Interactive threshold selection:**  
  Fine-tune campaign targeting based on business needs.
- **Top-N targeting:**  
  Instantly view and export the top N most probable target customers.
- **Explainable AI:**  
  Visual SHAP analysis for actionable business insight.
- **Professional UI:**  
  Modern interface, color-coded summaries, responsive layout.

---

## 👥 Contributors

| Name           | GitHub                                      |
|----------------|---------------------------------------------|
| Aida Abdolhosseini      | [your-github](aida.abdolhoseinii@gmail.com)   |
| Mohammad Gholami   | [teammate1](mohammadgholami7380@gmail.com)   |
| Roham Ghousi  | [teammate2](roham.ghousi@gmail.com)   |

Special thanks to all team members for their contribution and teamwork.

---

## 📄 License

MIT License (add a LICENSE file if you want)

---

## 📢 Citation

If you use this system or codebase in your research or business, please cite or mention the repository!

---

## 📨 Contact

For questions, issues, or feedback, open an [Issue](https://github.com/mamadqolami/bank-dss-app/issues) or contact the project maintainer.

---

