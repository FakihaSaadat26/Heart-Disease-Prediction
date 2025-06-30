# Heart-Disease-Prediction

## 🧠 Objective

The goal of this project is to build a machine learning model that can **predict whether an individual is at risk of heart disease** based on their clinical and personal health data.

---

## 🗂 Dataset

- **Source**: [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Features include**:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Maximum Heart Rate Achieved
  - Exercise Induced Angina
  - ST Depression
  - Number of major vessels
  - Thalassemia
  - Target (1 = heart disease, 0 = no heart disease)

---

## 🧰 Tools & Libraries

- Python
- `pandas`, `numpy` — data cleaning and manipulation
- `matplotlib`, `seaborn` — visualizations and EDA
- `scikit-learn` — modeling and evaluation

---

## 🔍 Workflow

1. **Data Cleaning**:
   - Handle missing values
   - Encode categorical variables

2. **Exploratory Data Analysis (EDA)**:
   - Understand variable distributions
   - Plot correlation heatmaps
   - Visualize class distribution

3. **Model Training**:
   - Train a **Logistic Regression** or **Decision Tree** classifier
   - Use `train_test_split()` for cross-validation

4. **Model Evaluation**:
   - Confusion Matrix
   - Accuracy Score
   - ROC Curve and AUC Score

5. **Feature Importance**:
   - Identify the most influential features in heart disease prediction

---

## 📈 Results

- Confusion Matrix showing TP, FP, TN, FN
- ROC Curve showing classification performance
- Feature importance plot highlighting key health indicators

---

## 📷 Example Outputs

### ✅ Confusion Matrix
![Confusion Matrix](assets/confusion_matrix.png)

### ✅ ROC Curve
![ROC Curve](assets/roc_curve.png)

### ✅ Feature Importance
![Feature Importance](assets/feature_importance.png)

---

## 🚀 How to Run

```bash
pip install pandas matplotlib seaborn scikit-learn
python heart_disease_predictor.py
