# 🎓 Jamboree-Admission-Prediction---Linear-Regression-Project
Jamboree Admissions - Linear Regression Model Predicting Chance of Admission Using Academic and Profile Data Dataset: 500 student profiles (GRE, TOEFL, CGPA, Research, etc.)


## 📌 Overview
This project uses linear regression to predict the **Chance of Admission** for graduate students based on their academic credentials. The data was sourced from a mock admissions dataset of 500 student profiles.

---

## 📁 Files Included
- `Jamboree_Education_Linear_Regression_Updated.ipynb` → Cleaned, finalized notebook with analysis, model building, and interpretation
- `Jamboree_Education_Linear_Regression_Final.pdf` → PDF report of the project (to be generated)

---

## 🔍 Features Used
- GRE Score
- TOEFL Score
- University Rating
- SOP & LOR strength
- CGPA
- Research Experience

---

## 📈 Model Summary
- **Model Used:** Linear Regression (compared with Ridge & Lasso)
- **R² Score:** 0.81
- **Best Features:** CGPA, GRE, TOEFL, Research
- **Feature Removed:** SOP (statistically insignificant)

---

## 💡 Key Business Insights
- CGPA is the **strongest predictor** of admission.
- Research experience boosts chances significantly.
- SOP was found **not statistically significant**, likely due to subjective evaluation.

---

## 🚀 Streamlit Web App
### To run locally:
```bash
pip install streamlit
streamlit run app.py
```

You’ll be able to enter inputs and get an instant prediction.

---

## 🛠️ Future Enhancements
- Add classification model (Admit vs Reject)
- Add a dashboard for profile strength scoring
- Deploy the app via Streamlit Cloud or HuggingFace Spaces

---

## 🙌 Author
Popatsing Waghela  
