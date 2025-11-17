<!-- PROJECT HEADER -->
<h1 align="center">🚀 A Data Analytics-Based System for Proactive Student Performance Monitoring and Personalized Learning Interventions</h1>
<p align="center">
  <i>End-to-End Modeling • Visualization • Explainability • SHAP • XGBoost • Random Forest</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ML-RandomForest%20%7C%20XGBoost-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Explainability-SHAP-red?style=for-the-badge"/>
</p>

---

## 📌 Overview
This repository contains a complete, interactive **machine learning pipeline** for analyzing activity-tracking data.  
It includes preprocessing, model training, performance evaluation, and modern explainability using **SHAP**.

The project is built in a Jupyter/Colab notebook and is easy to run, customize, and extend.

---

## 📂 Project Structure

📁 ML-Activity-Tracking/
│── 📓 Untitled15.ipynb # Main ML notebook
│── 📁 data/ # Uploaded dataset
│── 📄 README.md # Interactive documentation
│── 📄 requirements.txt # Python dependencies



---

## ✨ Features

### 🔧 Data Processing
- CSV uploading via Google Colab  
- Encoding fixes (`latin1`)  
- Handling categorical + numeric features  

### 🤖 Machine Learning
- **Random Forest Classifier**
- **XGBoost Classifier**
- Cross-validation support  
- Feature importance charts  

### 🧠 Explainability
- SHAP summary plot  
- Feature contribution visualization  
- Model interpretability  

### 📈 Visual Analytics
- Bar charts  
- SHAP summaries  
- Data previews  

---

## 🚀 Getting Started

### ▶️ Open Notebook in Google Colab
> _(If you upload this repo to GitHub, I can generate the proper Colab link.)_

---

### 📥 Install Dependencies
```bash
pip install pandas scikit-learn xgboost shap tensorflow matplotlib seaborn plotly






📤 Upload Your Dataset

from google.colab import files
uploaded = files.upload()


🧪 Run the Notebook

The notebook will:

Load & preprocess data

Train Random Forest and XGBoost

Display model performance

Generate SHAP explainability



🌱 Future Enhancements

Hyperparameter tuning (Optuna)

Add ROC/AUC plots

Export trained models

Add FastAPI endpoint

Add Docker support


👨‍💻 Author

Sahil
BE CSE AIML

📜 License & Copyright

Copyright © 2025 Sahil  
This project is licensed for personal and educational use.  
Unauthorized commercial use is not permitted without permission.
