# hospital-readmission-ml
# 🏥 Hospital Readmission Prediction using Machine Learning

This project predicts whether a patient is likely to be **readmitted to the hospital** using demographic and clinical data.  
It applies **Logistic Regression** and **Random Forest** models to identify key risk factors and improve healthcare efficiency.

---

## 📊 Dataset
- Source: Publicly available hospital readmission dataset (UCI / Kaggle)
- Records: 100,000+
- Key Features: 
  - Race, Gender, Age group  
  - Time in hospital, Number of lab procedures, Medications, Outpatient visits  
  - Readmission flag (target)

---

## ⚙️ Technologies Used
- Python 🐍  
- Jupyter Notebook  
- Pandas, NumPy, Scikit-learn  
- XGBoost, Matplotlib, Seaborn  
- SHAP for model explainability

---

## 🧠 Models and Accuracy
| Model | Accuracy | Key Notes |
|--------|-----------|-----------|
| Logistic Regression | 88.7% | Baseline model |
| Random Forest | 87.9% | Handles imbalance better |
| Balanced Logistic Regression | 68% | Focused on minority class |

---

## 📈 Visualizations
- Confusion Matrix (Performance)
- Feature Importance (Top 10 Predictors)
- SHAP Summary (Model Explainability)

---

## 💡 Key Insights
- **Number of lab procedures**, **medications**, and **time in hospital** are top predictors.  
- Random Forest performed better for rare readmission cases.  
- SHAP visualizations helped explain individual predictions for patients.

---

## 📂 Files in Repository
| File | Description |
|------|--------------|
| `hospital_readmission.ipynb` | Full Jupyter Notebook with preprocessing, modeling, and evaluation |
| `readmission_predictions.csv` | Model prediction results |
| `shap_summary.png` | SHAP summary visualization |
| `report.pdf` | Optional report version for sharing |
| `README.md` | This project summary |

---

## 🧑‍⚕️ Author
**Vaibhav Kondabathini**  
Master’s in Computer Science | Data Analytics Focus  
📍 University of Illinois Springfield  
💼 [LinkedIn Profile](https://www.linkedin.com/in/vaibhavkondabathini)  
📧 vaibhavkondabathini@gmail.com  

---

### ⭐ If you found this project useful, give it a star on GitHub!
