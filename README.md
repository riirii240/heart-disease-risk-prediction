# Heart Disease Risk Prediction
### Comparative Machine Learning Study in Healthcare

## 📌 Project Overview
Cardiovascular diseases are among the leading causes of death worldwide.
This project explores clinical patient data to estimate the risk of heart disease
using multiple machine learning models.

⚠️ This project is for educational purposes only and **is not a medical diagnostic tool**.

---

## 🎯 Objectives
- Analyze clinical features associated with heart disease
- Compare multiple machine learning classification models
- Evaluate models using appropriate medical metrics
- Highlight the importance of interpretability in healthcare ML

---

## 📊 Dataset
The dataset contains clinical and demographic information such as:
- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol level
- Maximum heart rate
- Exercise-induced angina

Target variable:
- `0` → No heart disease
- `1` → Presence of heart disease

---

## 🧪 Methodology
1. Data exploration and visualization (EDA)
2. Feature scaling
3. Train-test split
4. Model training:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Random Forest
5. Model evaluation using:
   - Accuracy
   - Recall
   - Confusion matrix
   - ROC curve
6. Validation using 5-fold cross-validation

---

## 📈 Results
- All models achieved comparable accuracy (≈ 86–88%)
- Random Forest showed the best average performance in cross-validation
- Logistic Regression provided strong interpretability with competitive results

In a medical context, recall and false negatives were prioritized over accuracy alone.

---

## ⚠️ Limitations
- Limited dataset size
- No longitudinal or demographic diversity analysis
- Models should not be used for real clinical decision-making

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Feature selection techniques
- Integration of explainability tools (e.g. SHAP)
- Testing on larger and more diverse datasets

---

## 🛠 Technologies Used
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📁 Files
- `Heart_Disease_ModelSelection.ipynb` — main analysis notebook
