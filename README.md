# Titanic Survival Prediction

This project applies machine learning classification models to predict passenger survival on the Titanic dataset (Kaggle).  
It demonstrates data preprocessing, feature engineering, model training, and evaluation.

---

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- Features:
  - Passenger demographics (`Age`, `Sex`, `Pclass`, `Embarked`)  
  - Travel info (`Fare`, `Cabin`, `Ticket`)  
  - Target: `Survived` (1 = Yes, 0 = No)  

---

## Methods & Models
The notebook explores multiple ML models:
- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- Cross-validation with SMOTE (for handling imbalance)

---

## Results
- Evaluated using:
  - Classification Report (Precision, Recall, F1-score)  
  - Confusion Matrix visualization  
- Compared model performances to identify the best approach.

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Imbalanced-learn (SMOTE)

---

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/MarcDagher8/Titanic_Survival_Prediction.git
