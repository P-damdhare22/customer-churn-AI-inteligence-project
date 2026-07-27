


# AI Customer Churn Intelligence Platform

A machine learning project that predicts customer churn, explains predictions 
using SHAP, and stores results — with an interactive Gradio dashboard for 
uploading data and viewing predictions.

## 🎯 What it does
- Predicts whether a customer is likely to churn based on their data
- Explains *why* using SHAP (shows which features influenced each prediction)
- Stores prediction history using SQLite
- Provides an interactive dashboard to upload a dataset, train a model, 
  and view predictions

## 🛠️ Tech Stack
- Python
- pandas, scikit-learn (data processing & ML model)
- SHAP (model explainability)
- SQLite (data storage)
- Gradio (dashboard interface)

## 📁 Dataset
Built and trained using the real **Kaggle Telco Customer Churn dataset** 
(7,043 customer records, including tenure, contract type, monthly charges, 
services used, and churn label).

# How it was built
This project was built with AI-assisted development using Claude, which 
helped write and structure the code. I tested and ran it in Google Colab 
to understand and verify how each part works — from data upload, to model 
training, to SHAP explanations, to the Gradio interface.

# Current Status
- Model and dashboard are working and tested in Google Colab
- Trained on the real Kaggle Telco Customer Churn dataset
- Currently using a temporary Gradio share link (expires after ~1 week, 
  as shown in the demo video)
- **Not yet permanently deployed** — next step is deploying via 
  Hugging Face Spaces for a permanent live link

# Demo
A working demo video is attached separately showing the dataset upload, 
model training, and prediction dashboard in action.

# How to Run (once code is added to repo)
git clone https://github.com/pr2355/customer-churn-AI-inteligence-project.git
cd customer-churn-AI-inteligence-project
pip install -r requirements.txt
python app.py

# Next Steps
- Deploy permanently on Hugging Face Spaces
- Improve model accuracy and add more features to the dashboard

# Author
Priyankaa — BCA Second Year Student, currently learning AI/ML & Data Science
