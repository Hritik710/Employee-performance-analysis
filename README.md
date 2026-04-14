# Employee Performance Prediction – Machine Learning Project
### IABAC Certified Data Scientist – Project Submission

---

## 📌 Project Overview
This project aims to predict **Employee Performance Ratings** using machine learning techniques applied to historical HR data.

The final model selected is **Random Forest Classifier (GridSearchCV tuned)** with a test accuracy of **94.17%**.

---

## 📂 Project Structure
```
project/
│
├── data/
│   ├── raw/                       
│   └── processed/                 
│
├── src/
│   ├── data_processing/
│   │   └── data_processing.ipynb
│   ├── eda/
│   │   └── exploratory_analysis.ipynb
│   ├── models/
│   │   ├── train_model.ipynb
│   │   └── predict_model.ipynb
│   └── visualization/
│       └── visualize.ipynb
│
├── models/
│   ├── final_random_forest_model.joblib
│   └── gridsearch_random_forest.joblib
│
└── Project Summary/
    ├── Requirement/
    ├── Analysis/
    └── Summary/
```

---

## 🚀 Final Model & Performance
- **Model:** Random Forest Classifier (GridSearchCV tuned)  
- **Accuracy:** **94.17%**  
- **Saved Model:**  
  ```
  models/final_random_forest_model.joblib
  ```

---

## 🔍 Top 3 Features Influencing Performance
1. **EmpLastSalaryHikePercent**  
2. **EmpEnvironmentSatisfaction**  
3. **YearsSinceLastPromotion**

These features have the strongest impact on employee performance based on model importance scores.

---

## 📈 Notebooks Overview

| Notebook | Description |
|----------|-------------|
| `data_processing.ipynb` | Data cleaning, encoding, preprocessing |
| `exploratory_analysis.ipynb` | EDA graphs, correlations, insights |
| `train_model.ipynb` | Model training, evaluation, GridSearchCV |
| `predict_model.ipynb` | Predicting performance using saved model |
| `visualize.ipynb` | Feature importance chart |

---

## 🧠 Business Insights

- Employees receiving **higher salary hikes** tend to show higher performance levels.  
- A high **environment satisfaction score** strongly influences productivity.  
- Employees recently promoted often display improved performance.

These insights help HR teams plan salary revisions, promotion cycles, and workplace improvements.

---

## ▶ How to Run This Project

### **1️⃣ Install Dependencies**
```
pip install -r requirements.txt
```

### **2️⃣ Train the Model**
Open:  
```
src/models/train_model.ipynb
```

### **3️⃣ Generate Predictions**
Run:  
```
src/models/predict_model.ipynb
```

Predictions will be saved in:  
```
data/processed/predicted_results.csv
```

### **4️⃣ View Feature Importance**
Open:  
```
src/visualization/visualize.ipynb
```

---

## Author
**Hritik**

---

## ✔ Submission Ready  
This project follows all **IABAC Certified Data Scientist** guidelines.

🎉 *Thank you for reviewing this project!*
