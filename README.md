# 📉 Customer Churn Prediction System 

This project is the 2nd task of my role as a **Machine Learning Intern** which predicts which customers are likely to leave a telecom service, using machine learning and visualizing key churn insights with Power BI.

---

## 🚀 Project Summary

Customer churn prediction helps businesses proactively retain customers by identifying those at risk of leaving. This project implements an end-to-end machine learning pipeline to:
- Clean and engineer features from customer data
- Handle class imbalance using SMOTE
- Train an optimized XGBoost classifier (chose the highest performing model)
- Evaluate churn probability and prediction accuracy
- Export predictions as `.csv`
- Build insightful dashboards in **Power BI**

---

## 📂 Project Structure

```bash
Customer_Churn_Prediction_System/
│
├── model/
│   ├── Customer_Churn_Prediction_System.ipynb              # Jupyter notebook for model training
│   └── churn_predictions.csv                               # Final output predictions
│
├── powerbi/
│   └── Customer Churn Prediction Dashboard.pbix            # Power BI dashboard 
│
├── sample dashboard image
│   └── Dashboard.png                                       # Screenshot of the dashboard
│
├── data/
│   └── raw_data.csv                                        # Source dataset
│
├── requirments/
│   └── requirements.txt                                    # Necessary for model building and use
│
└── README.md                                               # You're here!
```

---

## 🛠️ Technologies & Tools

| Category            | Tools / Libraries                                                  |
|---------------------|--------------------------------------------------------------------|
| Language            | Python                                                             |
| ML & Preprocessing  | XGBoost, Scikit-learn, Pandas, Numpy, Imbalanced-learn (SMOTE)     |
| Visualization       | Power BI, Matplotlib, Seaborn                                      |
| Output Formats      | CSV for predictions, PBIX for dashboard                            |

---

## ⚙️ Getting Started

1. **Clone the repository**  
```bash
git clone (https://github.com/Arkya-Sanyal-007/Future-ML-02.git
cd Future-ML-02
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Launch the notebook**  
```bash
jupyter notebook notebooks/Customer Churn Prediction System.ipynb
```

---

## 📌 Requirements

- Python 3.7+
- Jupyter Notebook
- Required libraries listed in requirements.txt

---

## 🧪 Model Training & Evaluation

- Model Used: **XGBoost Classifier**
- Dataset balanced using **SMOTE**
- Test Accuracy: `76.9%`
- ROC AUC Score: `0.81`

**Evaluation Metrics:**
- ✅ Confusion Matrix  
- ✅ Classification Report  
- ✅ ROC Curve  

---

## 📁 Output Predictions

Final predictions are exported to:  
📄 `churn_predictions.csv`  

**Columns Included:**
- `customerID`  
- `Churn Prediction` (0 = No, 1 = Yes)  
- `Churn Probability` (range from 0 to 1)  

---

## 🙋‍♂️ Author

**Arkya Sanyal**  
  
For any questions, contact : [arkyasanyal03@gmail.com](mailto:arkyasanyal03@gmail.com)  

---

## ⭐ Support

If you found this project helpful:
- 🌟 Star the repository
- 🤝 Connect with me on LinkedIn
- 📬 Drop a message if you have ideas or questions!

---

