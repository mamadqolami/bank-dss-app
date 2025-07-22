# bank-dss-app
# 💼 Bank Marketing DSS (Decision Support System)
A professional, fully-interpretable Decision Support System (DSS) for direct bank marketing campaigns, built with Streamlit and Python.

## 🚀 About the Project
This app helps marketing teams **select target customers for direct marketing campaigns in the banking sector**, using advanced machine learning models and ensemble (voting) techniques.  
The system is **trained on real-world, imbalanced bank marketing data** and leverages models such as XGBoost, LightGBM, and MLP, with oversampling strategies (SMOTE, ADASYN) for better performance.

**Key features:**
- Upload your own customer feature data (`X_test.csv`)
- Choose from several trained models or use the ensemble (Voting) option
- Adjust prediction threshold and view predicted target list
- Download the results as CSV
- View model interpretability with SHAP (feature importance) for the selected targets
- Modern, user-friendly interface (Streamlit, responsive, English UI)

## 📂 How to Use
1. **Open the app:**  
   👉 [Launch the DSS App Here](https://bank-dss-app-h6hv27fvhj29qphnznvk6n.streamlit.app)
2. **Upload your data:**  
   - Click on “Upload X_test.csv file” and select your feature file (the format must match the training data)
3. **Choose model and settings:**  
   - In the sidebar, select your desired model and threshold, and choose how many top targets to display
4. **Get predictions and insights:**  
   - View prediction results, download them as CSV, and see top features influencing each prediction

## 🛠️ Requirements
- All dependencies are managed by Streamlit Cloud;  
  (for local run: see `requirements.txt`)

## 📊 Models
Trained models included:
- XGBoost (raw / SMOTE / ADASYN)
- LightGBM (SMOTE)
- MLP (SMOTE)

## ⚡ Quick Start (for Developers)
Clone this repo and run:
```bash
pip install -r requirements.txt
streamlit run app.py
