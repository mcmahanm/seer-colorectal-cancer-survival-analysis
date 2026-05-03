# 📊 Predicting Colorectal Cancer Survival Using SEER Data

🔗 **Live Report:**  
https://mcmahanm.github.io/seer-colorectal-cancer-survival-analysis/

## 🔍 Overview
This project analyzes colorectal cancer survival outcomes using data from the SEER (Surveillance, Epidemiology, and End Results) program. The goal is to evaluate whether patient demographics and clinical characteristics can predict survival duration following diagnosis.

---

## 🧠 Key Features
- Cleaned and processed a large oncology dataset (198K+ records)
- Performed feature engineering and categorical encoding
- Built a multiple linear regression model
- Evaluated performance using R², MAE, and RMSE
- Interpreted results in a clinical oncology context

---

## 📁 Project Structure
- `notebook/` → Data preprocessing and model development  
- `report/` → Final analytical report (HTML)

---

## 📈 Model Performance
- R²: 0.31  
- MAE: 34.1 months  
- RMSE: 40.8 months  

---

## 🔑 Key Findings
- Cancer stage is the strongest predictor of survival  
- Localized disease significantly improves survival outcomes  
- Age ≥85 is associated with decreased survival  
- Diagnosis year shows a negative association due to right-censoring  

---

## ⚠️ Limitations
- Survival data includes censoring not fully captured by linear regression  
- Limited feature set (no treatment data, comorbidities, tumor grade)  

---

## 🏥 Applications
- Oncology risk stratification  
- Population health analytics  
- Early intervention strategy development  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Healthcare data analytics

---

## 📌 Author
Michaela McMahan  
Health Informatics & Revenue Cycle Professional
