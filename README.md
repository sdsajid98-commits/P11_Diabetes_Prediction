# Diabetes Prediction Using Machine Learning

This project predicts the likelihood of diabetes in individuals using various health and demographic features. It leverages classic machine learning models and provides an end-to-end workflow from data preprocessing to model evaluation.

---

## Features

- Predicts diabetes (Yes/No) based on health and demographic data.
- Handles categorical and numerical features.
- Supports multiple models: Logistic Regression, Decision Tree, Random Forest, and SVM.
- Provides detailed evaluation metrics including accuracy, confusion matrix, and classification report.
- Includes data exploration and visualization for better understanding of feature relationships.

---

## Dataset

- Source: `diabetes_dataset.csv`
- Size: 100,000 rows × 16 columns
- Features include:
  - year, gender, age, location
  - race indicators (AfricanAmerican, Asian, Caucasian, Hispanic, Other)
  - hypertension, heart_disease, smoking_history
  - bmi, hbA1c_level, blood_glucose_level
- Target: `diabetes` (0 = No, 1 = Yes)

---

## Libraries Used

- **Data Analysis:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Preprocessing & Model Selection:** scikit-learn (train_test_split, LabelEncoder)
- **Models:** LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, SVC
- **Evaluation:** accuracy_score, confusion_matrix, classification_report

---

## How to Run

1. Install required packages:
   pip install pandas numpy matplotlib seaborn scikit-learn

2. Place `diabetes_dataset.csv` in the same folder as the script.

3. Run the script:
   python diabetes_prediction.py

4. The workflow includes:
   - Data exploration and preprocessing
   - Training multiple machine learning models
   - Evaluating models using accuracy, confusion matrix, and classification report
   - Selecting the best model for prediction

---

## File Structure

project-folder/
│
├─ diabetes_prediction.py      # Main ML workflow script
├─ diabetes_dataset.csv        # Dataset used for training and testing
└─ README.md

---

## Notes

- This is a standard classification problem ideal for showcasing beginner-to-intermediate ML skills.
- Can be included in a portfolio under a "Healthcare ML Projects" or "Predictive Modeling" section.
- Visualization of feature-target relationships enhances interpretability.
- Model performance may vary depending on preprocessing steps and hyperparameters.
