# Machine Learning Based Prediction of Peak Load in EV Charging Stations

🎓 MSc Business Analytics Thesis | Dublin Business School

This repository presents my **Applied Research Project** focused on predicting **monthly peak electricity demand at Electric Vehicle (EV) charging stations** using machine learning techniques. The objective is to support **grid planning, infrastructure optimization, and energy management decisions**.

---

## 🎓 Research Context

With the rapid growth of electric vehicles, electricity demand patterns are becoming increasingly **non-linear and unpredictable**. Traditional forecasting methods struggle to capture these variations.

This research develops a **machine learning-based framework** to predict peak load demand at the **station level**, enabling better **resource allocation, infrastructure planning, and grid stability**.

---

## 🎯 Research Aim

To predict **monthly peak electricity demand (kWh)** at EV charging stations using historical charging data, temporal features, and weather variables.

---

## ❓ Research Questions

- Can peak load demand be accurately predicted using historical and weather data?  
- Which factors (temporal vs weather) influence peak demand the most?  
- Which machine learning model provides the best predictive performance?  
- How effective are ML models compared to traditional approaches?  

---

## 📊 Methodology

This study follows a **quantitative and comparative research approach**:

- Data collection from EV charging datasets and weather APIs  
- Data cleaning and preprocessing  
- Temporal aggregation (daily → monthly)  
- Feature engineering (temporal, seasonal, station-level)  
- Model training using time-based split  
- Hyperparameter tuning  
- Model evaluation using standard metrics  

---

## 📁 Dataset

- EV Charging Dataset: Palo Alto (Kaggle)  
- Time Period: ~10 years  
- Weather Data: Open-Meteo API  

### Key Features:
- Energy consumption (kWh)  
- Charging duration  
- Station identifiers  
- Temporal features (year, month, season)  
- Weather variables (temperature, humidity, wind, precipitation)  

---

## ⚙️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🤖 Models Implemented

- Linear Regression (Baseline)  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- XGBoost Regressor  
- Feedforward Neural Network  

---

## 📈 Evaluation Metrics

- R² (Coefficient of Determination)  
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  

---

## 📊 Results Summary

- **SVR** showed the most **stable and consistent performance**  
- **XGBoost** achieved the **highest validation accuracy** but showed overfitting  
- **Random Forest** performed moderately but struggled with peak spikes  
- **Neural Network** underperformed due to limited dataset size  

Overall model performance: **R² ≈ 0.49 – 0.61**

---

## 🔍 Key Findings

- Temporal features (Year, Month, Season) were **more influential than weather variables**  
- Monthly aggregation reduces short-term weather impact  
- Simpler models (SVR) can outperform complex models on structured datasets  
- Peak load forecasting is **moderately predictable**, not highly precise  

---

## 💡 Practical Implications

- Supports **grid operators** in reserve allocation  
- Helps in **EV infrastructure planning**  
- Identifies **seasonal demand trends**  
- Enables **data-driven energy management decisions**  

---

## 🚀 Future Work

- Include traffic, EV adoption, and socio-economic data  
- Apply deep learning models (LSTM, hybrid models)  
- Use multi-resolution forecasting (hourly + monthly)  
- Expand to multi-city or country-level datasets  

---

## 📎 Repository Contents

- Jupyter Notebook with full implementation  
- Data preprocessing and feature engineering  
- Model training and evaluation  

---

## ⚠️ Academic Note

This repository represents an academic research project submitted as part of a master's degree.  
The full thesis document is not shared to maintain academic integrity.

---

## 👤 Author

**Rahul Pagar**  
MSc Business Analytics  
Dublin Business School  

LinkedIn: www.linkedin.com/in/rahul-pagar1993
