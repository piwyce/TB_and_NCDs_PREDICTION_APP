# 🧑‍⚕️ TB Risk Prediction App  

[![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red)](https://streamlit.io/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
![Stars](https://img.shields.io/github/stars/your-username/your-repo-name?style=social)  
![Forks](https://img.shields.io/github/forks/your-username/your-repo-name?style=social)  

A machine learning powered **Streamlit web app** that predicts the **risk of developing Tuberculosis (TB)** among patients on ART, based on clinical and demographic features.  

This project combines **Public Health + Data Science + AI** to support early risk detection and better health outcomes.  

---
## 🌟 Features
✅ User-friendly web interface (built with Streamlit)  
✅ Input patient details such as age, sex, CD4 count, viral load, and Hb  
✅ Predicts **High TB Risk** or **Low TB Risk** instantly  
✅ Powered by a trained **Random Forest model**  
✅ Lightweight and deployable on Streamlit Cloud  

---
## 📂 Repository Structure
📂 your-repo-name/  
 ├── app.py                    
 ├── requirements.txt          
 ├── random_forest_model.pkl   
 ├── logistic_regression_model.pkl   
 └── README.md                 

---
## 🚀 How to Run Locally
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
pip install -r requirements.txt
streamlit run app.py
